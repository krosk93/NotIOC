<script>
    import Improvements from './Improvements.svelte';
    import E502 from './502.svelte';
    import Database from './Database.svelte';
    import BadAccess from './BadAccess.svelte';
    import Joomla from './Joomla.svelte';

    const rand = Math.floor(Math.random() * 100) + 1;
    if(rand >= 15 && rand < 20)
        document.querySelector('body').style.backgroundColor = '#f1f1f1';
</script>
{#if rand < 5}
    <E502 />
{:else if rand >= 5 && rand < 10}
    <Database />
{:else if rand >= 10 && rand < 15}
    <BadAccess />
{:else if rand >= 15 && rand < 20}
    <Joomla />
{:else}
    <Improvements fp={rand > 60} />
{/if}

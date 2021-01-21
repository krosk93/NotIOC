<script>
    import Improvements from './Improvements.svelte';
    import E502 from './502.svelte';
    import Database from './Database.svelte';
    import BadAccess from './BadAccess.svelte';

    const rand = Math.floor(Math.random() * 100) + 1;
</script>
{#if rand < 10}
    <E502 />
{:else if rand >= 10 && rand < 20}
    <Database />
{:else if rand >= 20 && rand < 25}
    <BadAccess />
{:else}
    <Improvements />
{/if}

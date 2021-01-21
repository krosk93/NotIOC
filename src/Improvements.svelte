<style>
    .container {
        width: 100%;
        padding-right: 15px;
        padding-left: 15px;
        margin-right: auto;
        margin-left: auto;
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        font-size: 1rem;
        font-weight: 400;
        line-height: 1.5;
        color: #212529;
        text-align: left;
        background-color: #fff
    }

    .text-center {
        text-align: center!important
    }

    .my-5 {
        margin-bottom: 3rem!important;
        margin-top: 3rem!important;
    }

    .display-4 {
        font-size: 3.5rem;
        font-weight: 300;
        line-height: 1.2;
    }

    .display-5 {
        font-weight: 500;
        line-height: 1.2;
    }

    .mx-auto {
        margin-right: auto!important
    }

    .mx-auto {
        margin-left: auto!important
    }
    .d-block {
        display: block!important
    }
     h2 {
        font-size: 2rem;
    }
    h2, h3 {
        margin-bottom: .5rem;
        font-family: inherit;
        font-weight: 500;
        line-height: 1.2;
        color: inherit;
    }
</style>

<script>
    export let fp = false;
</script>

<div class="container">
    <img src="./cortesia/img/logo.jpg"
    class="mx-auto d-block my-5"
    alt="Departament d'Educació">
</div>

<div class="container text-center">
    <h2 class="my-5 display-4">Estem treballant en la millora del campus IOC</h2>
    {#if fp}
    <h2 class="my-5 display-4">Per causes tècniques s'ajorna la publicació de les notes d'FP</h2>
    <h2 class="my-5 display-4">Molt aviat s'informarà de la nova data de publicació</h2>
    {/if}
    <h3 class="my-5 display-5"> </h3>
    <h3 class="my-5 display-6">Lamentem les molèsties ocasionades</h3>
</div>
<script context="module">
    export const prerender = true;
</script>

<script>
    import Counter from "$lib/Counter.svelte";
   
</script>

<svelte:head>
    <title>Home</title>
</svelte:head>
<section>
    <h1>Welcome to Coinmeca</h1>
    <div class="welcome">
        <p>Visit <a href="#coinmecalink">Coinmeca</a> to read more</p>
    </div>
   
    <Counter />
</section>

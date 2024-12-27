<script>
    let count = $state(0)
</script>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>


<h3>{count}</h3>
<button onclick={() => count++}>Increase</button>
<button onclick={() => count=0}>Reset</button>
<button onclick={() => count--}>Decrease</button>


<style>
    h3 {
        --size: 10rem;
        margin: 0 auto;
        font-size: 3rem;
        color: white;

        border-radius: 50%;
        padding: 1rem;
        background-color: darkorchid;
        width: var(--size);
        height: var(--size);
        display: grid;
        place-content: center;
    }
</style>
<script>
    let count = $state(0)
</script>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>


<h3>{count}</h3>
<button onclick={() => count++}>Increase</button>
<button onclick={() => count=0}>Reset</button>
<button onclick={() => count--}>Decrease</button>
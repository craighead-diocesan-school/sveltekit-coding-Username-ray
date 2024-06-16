<script>
  import Header from "$lib/Header.svelte"
  import CurrencyConverter from "../lib/CurrencyConverter.svelte"
  import HiButton from "../lib/HiButton.svelte"
  import ImageCard from "../lib/ImageCard.svelte"
  let count = 0
  function increment() {
    count = count + 1
  }
  function decrement() {
    count = count - 1
  }
  let name = ""
</script>

<Header />

<main>
  {#if name}
    <h1>Hello, {name}!</h1>
  {:else}
    <h1>Hello, stranger!</h1>
  {/if}

  <h2>SvelteKit</h2>

  <p>Welcome to coding with SvelteKit, a modern JavaScript framework that makes it easy to code great apps.</p>

  <p>Count: {count}</p>
  <button on:click={increment}>Increment</button>
  <button on:click={decrement}>Decrement</button>
</main>

<HiButton />

<CurrencyConverter />

<ImageCard />

<footer>
  <p>&copy; Craighead Diocesan School 2024</p>
</footer>

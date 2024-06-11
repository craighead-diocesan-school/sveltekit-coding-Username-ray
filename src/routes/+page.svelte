<script>
  import Header from "$lib/Header.svelte"
  import ImageCard from "../lib/ImageCard.svelte"
  let count = 0
  function increment() {
    count = count + 1
  }
  function decrement() {
    count = count - 1
  }
</script>

<Header />

<main>
  <h2>SvelteKit</h2>

  <p>Welcome to coding with SvelteKit, a modern JavaScript framework that makes it easy to code great apps.</p>

  <p>Count: {count}</p>
  <button on:click={increment}>Increment</button>
  <button on:click={decrement}>Decrement</button>
</main>

<ImageCard />

<footer>
  <p>&copy; Craighead Diocesan School 2024</p>
</footer>

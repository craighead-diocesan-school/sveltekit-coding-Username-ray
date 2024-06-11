<script>
  let name = "world"
</script>

<input bind:value={name} placeholder="Enter your name" />

<header class="hero">
  <div class="hero-body">
    <h1 class="title">Hello {name}!</h1>
    <h2 class="subtitle">Welcome to my site</h2>
  </div>
</header>

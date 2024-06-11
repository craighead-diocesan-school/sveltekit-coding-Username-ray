<script>
  let count = ""
  function converter() {
    count = count * 1.63
  }
</script>

<input bind:value={count} placeholder="Enter a price in USD" />
<button on:click={converter}><p>click here to convert to NZD</p></button>

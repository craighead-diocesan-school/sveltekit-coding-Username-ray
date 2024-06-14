<script>
  let input = ""
  let output = ""
  let convRate = 1.63
  function converter() {
    output = input * convRate
  }
</script>

<label>
  USD:
  <input bind:value={input} placeholder="Enter a price in USD" />
</label>

<button on:click={converter}><p>click here to convert to NZD</p></button>

<label>
  NZD:
  <input bind:value={output} placeholder="The price in NZD" />
</label>

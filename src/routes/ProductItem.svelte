<script>
  import { products } from "../lib/ProductList.svelte"
</script>

<ul>
  {#each products as products}
    <li>{products.name}, price: {products.price.toFixed(2)}, {products.description}</li>
  {/each}
</ul>

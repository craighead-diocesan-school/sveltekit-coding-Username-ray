<script>
  let role = "Admin"
</script>

<main>
  {#if role == "Admin"}
    <h1>Welcome, {role}!</h1>
    <h2>You have full access to the system.</h2>
  {:else}
    <h1>Welcome, {role}!</h1>
    <h2>Your acess is limited.</h2>
  {/if}
</main>

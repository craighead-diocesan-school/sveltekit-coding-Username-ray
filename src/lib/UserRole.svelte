<script>
  let role = "Admin"
</script>

<main>
  <h1>Welcome, {role}!</h1>
  {#if role == "Admin"}
    <h2>You have full access to the system.</h2>
  {:else if role == "Editor"}
    <h2>You can edit content but have limited access.</h2>
  {:else if role == "Guest"}
    <h2>You have view-only access.</h2>
  {:else}
    <h2>Your acess is limited.</h2>
  {/if}
</main>

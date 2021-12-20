<script>
  import '../app.css'
</script>

<svelte:body tabindex="0" />
<main>
  <slot />
</main>

<style>
  :global(body) {
    margin: 0;
    padding: 0;
    background: var(--gradient-4);
  }

  main {
    display: grid;
    place-items: center;
    height: 100vh;
  }
</style>

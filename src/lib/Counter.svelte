<svelte:options tag="my-counter" />

<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 3
  }
</script>

<button on:click={increment}>
  clicks: {count}
</button>

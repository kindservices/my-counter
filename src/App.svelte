<svelte:options tag="my-counter-app" />

<script lang="ts">
  import MyCounter from './lib/MyCounter.svelte'
</script>

<main>
  <div class="card">
    <MyCounter param_one="My Counter value set in App.svelte" />
  </div>

</main>
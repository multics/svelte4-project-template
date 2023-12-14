<script>
import Counter from './lib/Counter.svelte'
</script>

<div class="flex h-screen flex-col justify-center">
  <h1 class="text-center text-3xl">hello there!</h1>
  <p class="text-center">This is svelte 4 project - a pure svelte project.</p>
  <p class="text-center text-4xl font-bold text-blue-400">start from here: src/App.svelte</p>
  <Counter />
</div>

<style lang="postcss">
:global(html) {
  background-color: theme(colors.green.100);
}
</style>

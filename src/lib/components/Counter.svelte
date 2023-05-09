<script lang="ts">
  let counter = 0;
</script>

<div>
  <p class="font-semibold">Count: {counter}</p>
  <button on:click={()=>counter++} class="bg-blue-500 p-2 rounded text-gray-800 font-semibold">Increment</button>
</div>

<style>
  div > * {
    @apply mb-4;
  }
</style>
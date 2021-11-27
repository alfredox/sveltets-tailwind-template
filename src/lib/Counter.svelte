<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment} class="p-4 w-48 bg-red-100 text-red-800 rounded-full">
  Clicks: {count}
</button>

<script lang="ts">
  let count = 0;

  const increment = async() => {
    count++;
  }

</script>
<main>
  <button id="increment" on:click={increment}>Increment</button> <span>{count}</span>
</main>
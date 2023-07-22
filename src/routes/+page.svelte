<script>
  import { Button } from 'flowbite-svelte';

  let count = 1;
</script>

<div class='p-9 flex flex-col items-center justify-center gap-10'>
  <h1 class='text-6xl'>Flowbite 🧡 Svelte</h1>
  <div class='flex items-center gap-3 text-2xl'>
    <div>{count}</div>
    <Button size='lg' on:click={() => count++}>Press me</Button>
  </div>
</div>

<script>
  import {Alert} from "flowbite-svelte";
</script>

<h1 class="text-3xl mb-4">Default Alert</h1>

<div class="flex flex-col gap-4">
<Alert>
  <span class="font-medium">Default alert!</span> Change a few things up and try submitting again.
</Alert>
<Alert color="blue">
  <span class="font-medium">Info alert!</span> Change a few things up and try submitting again.
</Alert>
<Alert color="red">
  <span class="font-medium">Danger alert!</span> Change a few things up and try submitting again.
</Alert>
<Alert color="green">
  <span class="font-medium">Success alert!</span> Change a few things up and try submitting again.
</Alert>
<Alert color="yellow">
  <span class="font-medium">Warning alert!</span> Change a few things up and try submitting again.
</Alert>
<Alert color="dark">
  <span class="font-medium">Dark alert!</span> Change a few things up and try submitting again.
</Alert>
</div>

<h1 class="text-3xl my-4">Alert Customization Examples</h1>
<div class="flex flex-col gap-4">
<Alert class="p-8">
  <span class="font-medium">Default alert!</span> Change a few things up and try submitting again.
</Alert>
<Alert color="blue" class="text-xl">
  <span class="font-medium">Info alert!</span> Change a few things up and try submitting again.
</Alert>
</div>
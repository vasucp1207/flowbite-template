<script>
  import { ButtonGroup, Button, Label } from 'flowbite-svelte';
</script>

<div class='p-16'>
<Label color="red" class="mt-4 flex items-center font-bold italic">
  Default button <Button class="ml-2">Default</Button> 
</Label>
<div class="text-gray-900 dark:text-gray-100">
  <div class="py-4">Pills</div>
  <ButtonGroup class="space-x-px">
    <Button pill color="purple">Profile</Button>
    <Button pill color="purple">Settings</Button>
    <Button pill color="purple">Messages</Button>
  </ButtonGroup>
  <div class="py-4">Standard buttons</div>
  <ButtonGroup>
    <Button color="red">Profile</Button>
    <Button color="green">Settings</Button>
    <Button color="yellow">Messages</Button>
  </ButtonGroup>
  <div class="py-4">Outline</div>
  <ButtonGroup>
    <Button outline color="red">Profile</Button>
    <Button outline color="green">Settings</Button>
    <Button outline color="yellow">Messages</Button>
  </ButtonGroup>
  <div class="py-4">Gradient with shadows</div>
  <ButtonGroup>
    <Button gradient shadow="green" color="green">Profile</Button>
    <Button gradient shadow="pink" color="pink">Settings</Button>
    <Button gradient shadow="teal" color="teal">Messages</Button>
  </ButtonGroup>
  <div class="py-4">Dualtone gradient</div>
  <ButtonGroup class="space-x-px">
    <Button gradient color="purpleToBlue">Profile</Button>
    <Button gradient color="cyanToBlue">Settings</Button>
    <Button gradient color="greenToBlue">Messages</Button>
  </ButtonGroup>
</div>
</div>

<script>
  import { Avatar, Dropdown, DropdownHeader, DropdownItem, DropdownDivider, Tooltip } from "flowbite-svelte"
</script>

<h1 class="text-3xl mb-4">Default Accordion</h1>
<div class="flex gap-4">
  <Avatar src="https://flowbite-svelte.com/images/profile-picture-2.webp"/>
  <Avatar src="https://flowbite-svelte.com/images/profile-picture-2.webp" rounded/>
  <Avatar src="https://flowbite-svelte.com/images/profile-picture-2.webp" border/>
  <Avatar src="https://flowbite-svelte.com/images/profile-picture-2.webp" border class="ring-red-400 dark:ring-red-300"/>
  </div>
  <div class="flex gap-4 my-4">
  <Avatar />
  <Avatar rounded />
  <Avatar border />
  <Avatar rounded border />
  <Avatar>JL</Avatar>
  </div>
  <div class="flex gap-4">
  <Avatar data-name="Jese Leos" rounded src="https://flowbite-svelte.com//images/profile-picture-1.webp"/>
  <Avatar data-name="Robert Gouth" rounded src="https://flowbite-svelte.com//images/profile-picture-2.webp"/>
  <Avatar data-name="Bonnie Green" rounded src="https://flowbite-svelte.com//images/profile-picture-3.webp"/>
  <Tooltip triggeredBy="[data-name]" on:show={e => name = e.target.dataset.name}>{name}</Tooltip>
</div>

<h1 class="text-3xl my-4">Avatar Customization Examples</h1>
<div class="flex gap-4">
  <Avatar classPlaceholder="text-red-500 bg-red-300"/>
  <Avatar rounded class="w-20 h-20"/>
</div>
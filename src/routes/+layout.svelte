<script>
	import '../app.postcss';
	  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte'
</script>

<main>
<Navbar let:hidden let:toggle>
  <NavBrand href="/">
    <img
      src="https://flowbite-svelte.com/images/flowbite-svelte-icon-logo.svg"
      class="mr-3 h-6 sm:h-9"
      alt="Flowbite Svelte Logo"
    />
    <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">
      Flowbite Svelte
    </span>
  </NavBrand>
  <NavHamburger on:click={toggle} />
  <NavUl {hidden}>
    <NavLi href="/" active={true} rel="external">Home</NavLi>
    <NavLi href="https://flowbite-svelte.com/" target="_blank">Flowbite Svelte</NavLi>
    <NavLi href="https://flowbite-svelte.com/docs/pages/quickstart" rel="external" target="_blank">Quickstart</NavLi>
    <NavLi href="https://flowbite-svelte.com/docs/pages/introduction" rel="external" target="_blank">Docs</NavLi>
    <NavLi href="https://flowbite-svelte.com/docs/components/accordion" target="_blank">Components</NavLi>
    <NavLi href="https://github.com/themesberg/flowbite-svelte" target="_blank">GitHub</NavLi>
  </NavUl>
</Navbar>
  <div class='p-8'>
    <slot />
  </div>
</main>

<script>
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte'
  </script>

<Navbar let:hidden let:toggle>
    <NavBrand href="/">
      Roknos
    </NavBrand>
    <NavHamburger on:click={toggle} />
    <NavUl {hidden}>
      <NavLi href="/" active={true}>Home</NavLi>
    </NavUl>
  </Navbar>
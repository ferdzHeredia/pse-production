<template>
  <mdb-navbar color="blue-gradient color-block-5 " dark>
    <mdb-navbar-brand :to="{ name: 'Home' }" >
      PSE
    </mdb-navbar-brand>
    <mdb-navbar-toggler>
      <mdb-navbar-nav>
        <mdb-nav-item :to="{ name: 'Home' }">Home</mdb-nav-item>
        <mdb-nav-item :to="{ name: 'About' }">About</mdb-nav-item>
        <mdb-nav-item :to="{ name: 'Team' }">Team</mdb-nav-item>
        <mdb-dropdown tag="li" class="nav-item">
          <mdb-dropdown-toggle tag="a" navLink color="primary-color #4285F4" slot="toggle" waves-fixed>Categories</mdb-dropdown-toggle>
          <mdb-dropdown-menu>
            <mdb-dropdown-item>Algebra</mdb-dropdown-item>
            <mdb-dropdown-item>Geometry</mdb-dropdown-item>
            <mdb-dropdown-item>Fractions</mdb-dropdown-item>
          </mdb-dropdown-menu>
        </mdb-dropdown>
      </mdb-navbar-nav>
      <form>
        <mdb-input type="text" class="text-white" placeholder="Search" aria-label="Search" label navInput waves waves-fixed/>
      </form>
    </mdb-navbar-toggler>
  </mdb-navbar>
</template>
<script>
  import { mdbNavbar, mdbNavbarBrand, mdbNavbarToggler, mdbNavbarNav, mdbNavItem, mdbDropdown, mdbDropdownMenu, mdbDropdownToggle, mdbInput, mdbDropdownItem } from 'mdbvue';
  export default {
    name: 'Navbar',
    components: {
      mdbNavbar,
      mdbNavbarBrand,
      mdbNavbarToggler,
      mdbNavbarNav,
      mdbNavItem,
      mdbDropdown,
      mdbDropdownMenu,
      mdbDropdownToggle,
      mdbDropdownItem,
      mdbInput
    }
  }
</script>
<template>
  <div class="headerhead">
    <b-navbar toggleable="lg">
      <b-navbar-toggle style="color:black; height:80px" target="nav-collapse"
        >☰</b-navbar-toggle
      >
      <div class="logogood">
        <img
          src="img/images/logogood.svg"
          style="width:150px; height:100px; margin:0px"
          alt="Good Morning"
        />
      </div>
      <div>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item style="color:white"
              ><router-link to="/">Accueil</router-link></b-nav-item
            >
            <b-nav-item
              ><router-link to="#">Tarifs</router-link></b-nav-item
            >
            <b-nav-item
              ><router-link to="/contact">Contact</router-link></b-nav-item
            >
            <b-nav-item><router-link to="#">Actu</router-link></b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>
<script>
import {
  BNavbar,
  BNavbarBrand,
  BNavbarToggle,
  BNavbarNav,
} from "bootstrap-vue/esm/components/navbar";
import { BCollapse } from "bootstrap-vue/esm/components/collapse";
import {
  BNavItem,
  BNavItemDropdown,
  BNavForm,
} from "bootstrap-vue/esm/components/nav";
import { BDropdownItem } from "bootstrap-vue/esm/components/dropdown";
import { BFormInput } from "bootstrap-vue/esm/components/form-input";
import { BButton } from "bootstrap-vue/esm/components/button";

export default {
  components: {
    BNavbar,
    BNavbarBrand,
    BNavbarToggle,
    BCollapse,
    BNavbarNav,
    BNavItem,
    BNavItemDropdown,
    BDropdownItem,
    BNavForm,
    BFormInput,
    BButton,
  },
};
</script>
<style>
.nav-item {
  color: white;
}
</style>

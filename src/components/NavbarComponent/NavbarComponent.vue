<template>
  <div class="navbar">
    <div class="container">
      <ul class="nav">
        <li class="logo">
          <router-link to="/">
            <img
              class="img-logo"
              src="../../assets/solid.svg"
              alt="navbar-logo"
          /></router-link>
        </li>
        <li class="menus">
          <ul>
            <li><router-link to="/speakers">Speakers</router-link></li>
            <li><router-link to="/portfolio">Schedule</router-link></li>
            <li><router-link to="/about">About</router-link></li>
            <li><router-link to="/sponsors">Sponsors</router-link></li>
            <li><router-link to="/contact">Contact</router-link></li>
          </ul>
        </li>
        <li class="actions">
          <div class="toggle-theme" @click="changeColor">
            Light
            <span class="back">
              <span class="inner" :class="isLight ? 'light' : 'dark'"></span>
            </span>
            Dark
          </div>
          <button>Contact us</button>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isLight: true,
    };
  },
  methods: {
    changeColor() {
      this.isLight = !this.isLight;
    },
  },
};
</script>

<style lang="scss" scoped>
@import "./NavbarComponent.style.scss";
</style>

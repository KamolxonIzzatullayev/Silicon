<template>
  <div class="cm-navbar">
    <Container>
      <nav class="nav">
        <ul class="nav-list">
          <li class="nav-list__logo">
            <a href="#">
              <img src="@/assets/images/navbar/Logo.svg" alt="Logo" />
            </a>
          </li>
          <li class="nav-list__item">
            <a href="#">Features</a>
          </li>
          <li class="nav-list__item">
            <a href="#">Overview</a>
          </li>
          <li class="nav-list__item">
            <a href="#">Store</a>
          </li>
          <li class="nav-list__item">
            <a href="#">Blog</a>
          </li>
          <li class="nav-list__item">
            <a href="#">Contact</a>
          </li>
        </ul>
        <button class="nav__btn">
          <img src="@/assets/images/navbar/up.svg" alt="Registration" /><span
            class="ml-2"
            >Sign in / up</span
          >
        </button>
      </nav>
    </Container>
  </div>
</template>

<script>
import Container from "../Container/Container.vue";
export default {
  name: "NavbarView",
  components: {
    Container,
  },
};
</script>

<style lang="scss" scoped>
@import "./NavbarView.style.scss";
</style>

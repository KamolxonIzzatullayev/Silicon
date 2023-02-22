<template>
    <div class="cm-navbar">
        <section>
            <Container>
                <nav class="nav flex justify-between">
                    <ul class="nav-list flex items-center">
                        <li class="nav-list__logo">
                            <a href="#">
                                <img
                                    src="@/assets/navbar/Logo.svg"
                                    alt="Logo"
                                />
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
                    <button class="nav__btn flex items-center">
                        <img
                            src="@/assets/navbar/up.svg"
                            alt="Registration"
                        /><span class="ml-2">Sign in / up</span>
                    </button>
                </nav>
            </Container>
        </section>
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

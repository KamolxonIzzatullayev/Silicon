<template>
    <div class="v-home">
        <NavbarViewVue></NavbarViewVue>
    </div>
</template>

<script>
import NavbarViewVue from "@/components/Common/Navbar/NavbarView.vue";
export default {
    name: "HomeView",
    components: {
        NavbarViewVue,
    },
};
</script>
<style lang="scss" scoped>
@import "./HomeView.style.scss";
</style>

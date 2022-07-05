<template>
  <div class="home">
    <HeaderSection />
  </div>
</template>

<script>
import HeaderSection from "@/components/HeaderSection.vue/HeaderSection.vue";
export default {
  name: "HomeView",
  components: { HeaderSection },
};
</script>

<style lang="scss" scoped>
@import "./HomeView.style.scss";
</style>

<template>
  <div class="header">
    <div class="nav" style="z-index: 2">
      <NavbarComponent />
    </div>
    <div class="intro">
      <img src="../../assets/image-video.png" alt="image-video" />
      <div class="title">
        <div class="text">
          <h3>Oct 14-15, 2021</h3>
          <h1>NY Digital Conference</h1>
        </div>
        <div class="location">
          <img src="../../assets/location.png" alt="location icon" />
          International Convention Centre, New York, USA
        </div>
        <div class="btn-groups">
          <button class="dark">Buy access pass</button>
          <button class="light">
            <img src="../../assets/icon-l.png" alt="calendar" /> Add to calendar
          </button>
        </div>
        <div class="clients">
          <div class="img-groups">
            <img class="first" src="../../assets/client-3.png" alt="client-3" />
            <img src="../../assets/client-2.png" alt="client-2" />
            <img src="../../assets/client-1.png" alt="client-1" />
          </div>
          <span class="clients-number"> 400+ </span>
          attendees are already with us
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavbarComponent from "../NavbarComponent/NavbarComponent.vue";
export default {
  data() {
    return {
      mess: "Kamolxon",
    };
  },
  components: { NavbarComponent },
};
</script>

<style lang="scss" scoped>
@import "./HeaderSection.style.scss";
</style>

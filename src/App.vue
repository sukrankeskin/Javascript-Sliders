<template>
  <Splide :options="{ rewind: true }" aria-label="My Favorite Images">
    <SplideSlide>
      <img src="./assets/bg.jpg" alt="Sample 1" style="height: 100vh" />
    </SplideSlide>
    <SplideSlide>
      <img src="./assets/bg.jpg" alt="Sample 2" style="height: 100vh" />
    </SplideSlide>
  </Splide>
</template>

<script>
import { Splide, SplideSlide } from "@splidejs/vue-splide";

export default {
  name: "App",
  components: {
    Splide,
    SplideSlide,
  },
};
</script>

<style>
@import "@splidejs/vue-splide/css";

@import "@splidejs/vue-splide/css/skyblue";
@import "@splidejs/vue-splide/css/sea-green";

@import "@splidejs/vue-splide/css/core";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

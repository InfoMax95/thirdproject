<template>
  <div>
    <MyHeader />
    <MyCarousel />
    <MyMain />
  </div>
</template>

<script>
import MyHeader from "./components/MyHeader.vue";
import MyCarousel from "./components/MyCarousel.vue";
import MyMain from "./components/MyMain.vue";

export default {
  name: "App",
  components: {
    MyHeader,
    MyCarousel,
    MyMain,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;
}
</style>

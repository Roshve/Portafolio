<template>
  <div id="app">
    <port-home />
  </div>
</template>

<script>
import PortHome from "./views/PortHome.vue";
export default {
  name: "App",
  components: {
    PortHome,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/index.scss";

#app {
  background: #f0f0f6;
}
</style>

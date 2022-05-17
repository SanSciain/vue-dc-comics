<template>
  <div id="app">
    <AppHeader />
    <main>--Contant goes here--</main>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>

<style lang="scss">
#app {
  @import "./style/common.scss";

  main {
    background-color: black;
    color: white;
    height: 100px;
  }
}
</style>

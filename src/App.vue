<template>
  <div id="app">
    <TheHeader />
    <TheMain />
    <TheFooter />
  </div>
</template>

<script>
  import TheHeader from "./components/TheHeader.vue";
  import TheMain from "./components/TheMain.vue";
  import TheFooter from "./components/TheFooter.vue";

  export default {
    name: "App",
    components: {
      TheHeader,
      TheMain,
      TheFooter,
    },
  };
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap.scss";
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>

<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
      <viewport />
  </div>
</template>

<script>
import ViewPort from "@/components/ViewPort.vue";
// import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    // HelloWorld
    viewport: ViewPort
  }
};
</script>

<style>
html,
body {
  width: 100%;
  height: 100%;
  overflow: hidden;
}
body {
  margin: 0px;
}
#app {
  height: 100%;
}
</style>

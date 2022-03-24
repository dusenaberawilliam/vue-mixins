<template>
  <div id="app">
    <CountOnClick />
    <p>___________________</p>
    <CountOnHover />
  </div>
</template>

<script>
import CountOnClick from "./components/CountOnClick.vue";
import CountOnHover from "./components/CountOnHover.vue";
export default {
  name: "App",
  components: {
    CountOnClick,
    CountOnHover,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

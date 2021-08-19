<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <com404></com404>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import { com404 } from "@kitc/shared";
console.log(com404);
export default {
  name: "App",
  components: {
    HelloWorld,
    com404,
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

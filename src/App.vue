<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <FootBar></FootBar>
  </div>
</template>

<script>
import FootBar from "@/components/FootBar";

export default {
  name: "App",
  components: {
    "FootBar": FootBar
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <FirstTitle />
    <Jumbotron />
  </div>
</template>

<script>
import FirstTitle from "@/components/FirstTitle.vue";
import Jumbotron from "@/components/Jumbotron.vue";
export default {
  name: "App",
  components: { FirstTitle, Jumbotron },
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
  height: 100vh;
}
</style>

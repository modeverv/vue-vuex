<template>
<div id="app">
  <vue-header></vue-header>
  <time-line></time-line>
</div>
</template>

<script>
import VueHeader from "@/components/Header"
import TimeLine from "@/components/TimeLine"

export default {
  name: "App",
  components: {
    VueHeader,
    TimeLine
  }
};
</script>

<style>
/*
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*/
</style>

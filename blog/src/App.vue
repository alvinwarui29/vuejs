<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HomeMy data="Hello from props " msg="Its Alvin here "/>
  </div>
</template>

<script>
import HomeMy from "./components/Home.vue";

export default {
  name: "App",
  components: {
    HomeMy,
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

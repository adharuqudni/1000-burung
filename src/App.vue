
<template>
  <div id="app">
    <div v-for="(n, index) in 1000" :key="index">
    <img alt="Vue logo" src="./assets/burung.jpg" />
    </div>
  </div>
</template>

<script>

export default {
  name: "App",
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

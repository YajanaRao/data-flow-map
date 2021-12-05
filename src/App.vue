<template>
  <div id="app">
    <DataFlow />
  </div>
</template>

<script>
import DataFlow from "./components/DataFlow";

export default {
  name: "App",
  components: {
    DataFlow,
  },
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

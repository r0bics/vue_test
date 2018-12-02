<template>
  <div id="app"><my-wizard /></div>
</template>

<script>
import MyWizard from "./components/MyWizard";

export default {
  name: "App",
  components: {
    MyWizard
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

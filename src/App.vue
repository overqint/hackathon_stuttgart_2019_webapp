<template>
  <div id="app">
    <Oben/>
    <Hauptteil msg="hallo"/>
  </div>
</template>

<script>
import Oben from "./components/Oben.vue";

export default {
  name: "app",
  components: {
    Oben
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
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  -o-box-sizing: border-box;
  box-sizing: border-box;

  /* width: 340px;
  height: 568px; */
  width: 400px;
  height: 700px;
  margin: auto;
  z-index: -10;
  background: url("assets/iphone-se-png-5.png") no-repeat center;
}
</style>

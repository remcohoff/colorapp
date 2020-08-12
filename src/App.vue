<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Hello />
    <ColorForm />
    <HelloWorld msg="Geef de pagina een achtergrondkleur" />
  </div>
</template>

<script>
import ColorForm from "./components/ColorForm.vue";
import Hello from "./components/Hello.vue";
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    ColorForm,
    Hello,
    HelloWorld
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
  padding-top: 60px;
  width: 100vw;
  height: 100vh;
}
</style>

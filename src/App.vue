<template>
  <HelloWorld msg="Hello Vue 3 in CodeSandbox!" />
  <MainMenu />
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
import MainMenuVue from "./components/MainMenu.vue";
export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
    MainMenu: MainMenuVue,
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

<template>
  <div id="app">
    <Header></Header>
    <Preview></Preview>
    <router-view></router-view>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Preview from "@/components/Preview";

export default {
  name: "App",
  components: { Header, Preview },
};
</script>

<style>
:root {
  box-sizing: border-box;
}
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: inherit;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

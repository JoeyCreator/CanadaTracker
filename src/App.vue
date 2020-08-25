<template>
  <div id="app">
    <Home msg="Hello Vue in CodeSandbox!"/>
  </div>
</template>

<script>
import Home from "./views/Home";
export default {
  name: "App",
  components: {
    Home
  }
};
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        width: 100%;
        height: 100%;
    }
    .fade-enter-active,
    .fade-leave-active {
        transition-duration: 0.3s;
        transition-property: height, opacity;
        transition-timing-function: ease;
        overflow: hidden;
    }
    .fade-enter,
    .fade-leave-active {
        opacity: 0
    }
</style>
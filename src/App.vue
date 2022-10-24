<template>
  <PxErrorPage message="This is an error message" icon=""></PxErrorPage>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 in CodeSandbox!" />
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
import PxErrorPage from "./components/PxErrorPage.vue";
export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
    PxErrorPage,
  },
  // errorCaptured(err, comp, info) {
  //   this.$refs.err.innerHTML = "we have an error";
  //   console.log(err);
  // },
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
/* .err {
  position: fixed;
  z-index: 9999;
  padding: 28px;
  background-color: red;
} */
</style>

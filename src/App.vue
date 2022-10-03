<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <MyMain/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MyMain from './Views/MyMain.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    MyMain,
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

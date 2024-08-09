<template>
    <div id="app">
      <NavBar msg="welcome to your vue.js app"/>
      <jumbotron/>
    </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import jumbotron from './components/jumbotron.vue';
export default {
  name: 'App',
  components: {
    NavBar,
    jumbotron
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

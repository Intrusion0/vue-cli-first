<template>
  <div id="app">
    <myTitle />
    <jumbotron />
  </div>
</template>

<script>
// import Title from './components/title.vue'
import myTitle from './components/myTitle.vue';
import jumbotron from './components/Jumbotron.vue';

export default {
  name: 'App',
  components: {
    myTitle,
    jumbotron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

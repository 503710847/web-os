<template>
  <div id="app">
    <RootPane></RootPane>
  </div>
</template>

<script>
  import RootPane from './components/RootPane.vue';

  export default {
    name: 'App',
    components: {RootPane}
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /*text-align: center;*/
    /*color: #2c3e50;*/
    /*margin-top: 60px;*/
    width: 100%;
    height: 100%;
  }
</style>

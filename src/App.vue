<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>
<script>

export default {
  name: 'App'
}
</script>

<style lang="scss">
 /* @import './assets/main.css'; */

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #117fec;
  margin-top: 60px;
}
</style>

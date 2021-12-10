<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Title/>
    <Jambo/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Jambo from './components/Jambo.vue'

export default {
  name: 'App',
  components: {
    Title,
    Jambo,
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
  background-color: black;
  height: 100vh;
}
</style>

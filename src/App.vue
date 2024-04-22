<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div>
    <input type="text" 
      v-model="simpleText">
  </div>
  <h1>{{ simpleText }}</h1>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      simpleText: 'demo text'
    }
  },
}
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

<template>
  <h1>Form</h1>
  <signup></signup>
</template>

<script>

import signupform from "./components/Signupform.vue"
export default {
  name: 'App',
  components: {
    signup:signupform,
    
  }
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
body{
  background-color: blanchedalmond;
  margin: 0;
}
</style>

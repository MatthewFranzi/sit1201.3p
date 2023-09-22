
<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About Me</router-link> |
    <router-link to="/projects">Notable Projects</router-link> |
    <router-link to="/contact">Contact</router-link>
  </nav>
  <router-view/>
</template>
<script>
export default {
  name: 'App',
  components: {}
}
</script>
<style>
#app {
  
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #020202;
}
</style>

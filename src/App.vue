<template>
  <div id="app">
    <AppNav />
    <router-view/>
  </div>
</template>

<script>
import AppNav from './components/AppNav.vue'

export default {
  name: 'App',
  components: { AppNav }
}
</script>

<style>
#app{
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: bold;
}
/* nav a.router-link-exact-active {
  color: #42b983;
} */
</style>

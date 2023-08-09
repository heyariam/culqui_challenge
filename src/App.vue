<template>
  <div>
    <Sideimage/>

  </div>
</template>

<script>
//import DashboardPanel from './pages/main/Dashboard.vue'
//import LoginForm from './pages/login/Login.vue'
import Sideimage from './pages/login/imageside.vue'

export default {
  name: 'App',
  components: {
    //LoginForm,
    //DashboardPanel
    Sideimage
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
}
</style>

<template>
  <div>
    <LoginForm/>

  </div>
</template>

<script>
//import DashboardPanel from './pages/main/Dashboard.vue'
import LoginForm from './pages/login/Login.vue'

export default {
  name: 'App',
  components: {
    LoginForm,
    //DashboardPanel
  
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
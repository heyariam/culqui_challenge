<template>
  <div>
    <DashboardPanel />
  </div>
</template>

<script>
import DashboardPanel from './pages/master/Dashboard.vue'
export default {
  name: 'App',
  components: {
    DashboardPanel

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

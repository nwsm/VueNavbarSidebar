<template>
  <div id="app">
    <NavBar></NavBar>
    <div>
      <SideBar></SideBar>
    </div>
    <div id="router-container">
      <router-view/>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar'
import SideBar from './components/SideBar'

export default {
  name: 'App',
  components: { NavBar, SideBar }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#router-container {
  margin-top: 60px;
}
</style>

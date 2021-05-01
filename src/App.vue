<template>
  <NavBar />
  <SideBar />
  <CardAttribute />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import SideBar from './components/SideBar.vue'
import NavBar from './components/NavigationBar.vue'
import CardAttribute from './components/CardAttribute.vue'
export default {
  name: 'App',
  components: {
    SideBar,
    NavBar,
    CardAttribute
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
    background: #f1f6f9;
    overflow: auto;
}
</style>

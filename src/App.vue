<template>
  <nav>
    <!-- <router-link to="/">Home</router-link> | -->
    <!-- <router-link to="/about">About</router-link> -->
  </nav>
  <router-view/>
  <Navbar/>
  <Home/>
</template>

<script>
import Home from './components/HelloWorld.vue'
import Navbar from './components/NavBar.vue'

export default ({
  components: {Home, Navbar}
})
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  background-color: #B1DDF1;
  /* overflow-x: hidden; */
}

</style>

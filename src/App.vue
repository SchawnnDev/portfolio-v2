<template>
  <div id="app">
    <div class="container">
      <presentation/>
      <NavBar/>
    </div>
  </div>
</template>

<script>

import Presentation from "@/components/Presentation"
import NavBar from "@/components/NavBar"

export default {
  name: 'App',
  components: {
    Presentation,
    NavBar
  }
}
</script>

<style>
* {
  font-family: 'Karla', sans-serif;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container {
  margin-left: 20%;
  margin-right: 20%;

  border: #2c3e50 solid 2px;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}


</style>

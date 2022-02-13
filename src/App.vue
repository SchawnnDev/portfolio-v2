<template>
  <div id="app">
    <div class="container">
      <presentation/>
      <projects/>
      <competences/>
    </div>
  </div>
</template>

<script>

import Presentation from "@/components/Presentation"
import Projects from "@/components/Projects";
import Competences from "@/components/Competences";

export default {
  name: 'App',
  components: {
    Competences,
    Projects,
    Presentation,
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

.title {
  margin-left: 50px;
  margin-right: 50px;
}

.title h1 {
  text-align: left;
  margin-bottom: 10px;
}

.title hr {
}
</style>

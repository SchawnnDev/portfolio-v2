<template>
<div>
  <a class="network" href="https://www.linkedin.com/in/paul-meyer-971270173/" target="_blank"><linkedin-icon size="48"/></a>
  <a class="network" href="https://github.com/SchawnnDev"><github-icon size="48"/></a>
</div>
</template>

<script>
import LinkedinIcon from 'vue-material-design-icons/Linkedin.vue'
import GithubIcon from 'vue-material-design-icons/Github.vue'

export default {
  name: "Networks",
  components: {
    LinkedinIcon,
    GithubIcon
  }
}
</script>

<style scoped>
a.network, a:hover.network, a:visited.network, a:active.network {
  color: black;
  text-decoration: none;
}
</style>
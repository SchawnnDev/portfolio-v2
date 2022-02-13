<template>
  <div class="navbar">
    <div>
      <chevron-double-left-icon size="36"/>
      <b>Mon CV</b>
    </div>
    <div>
      <b>Mes projets</b>
      <chevron-double-right-icon size="36"/>
    </div>
  </div>
</template>

<script>
import ChevronDoubleRightIcon from "vue-material-design-icons/ChevronDoubleRight.vue"
import ChevronDoubleLeftIcon from "vue-material-design-icons/ChevronDoubleLeft.vue"

export default {
  name: "NavBar",
  components: {
    ChevronDoubleRightIcon,
    ChevronDoubleLeftIcon
  },
  props: {
    page: {
      default: 0,
      type: Number
    }
  }
}
</script>

<style scoped>
.navbar {
  height: 50px;
  width: 100%;
  border-top: 2px #2c3e50 solid;
  display: flex;
  justify-content: space-between;
}
</style>
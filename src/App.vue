<script>
import NavBar from './components/NavBar.vue'
import TopHome from './components/TopHome.vue'
import USP from './components/USP.vue'
export default {
  name: 'App',
  components: {
    NavBar,
    TopHome,
    USP,
  }
}
</script>

<template>
  <NavBar />
  <TopHome />
  <USP />
</template>

<style scoped>
</style>

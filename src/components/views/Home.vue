<template>
  <div>
    <header></header>
    Home
    <nav-menu></nav-menu>
    <router-view/>
  </div>
</template>

<script>
import Header from '../common/Header'
import NavMenu from '../common/NavMenu'
export default {
  name: 'Home',
  components: {Header, NavMenu}
}
</script>

<style scoped>

</style>

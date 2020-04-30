<template>
  <div id="dashboard">
      <LeftMenu LeftMenu_Title="Titi"/>
      <Historic Historic_Title="Oulala"/>
    <Footer Footer_Title="Toast"/>

  </div>
</template>

<script>
import LeftMenu from './LeftMenu.vue'
import Historic from './Historic.vue'
import Footer from './Footer.vue'

export default {
  name: 'App',
  components: {
    Footer,
    LeftMenu,
    Historic
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
</style>

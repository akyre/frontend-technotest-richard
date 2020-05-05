<template>
  <div id="Historic_page">
      <NavBar Navbar_Title="Test"/>
      <div class="historic-title">
        <h3 class="nav-section-title">Historic</h3>

        <Historic Commentary="Katli"/>

        <Historic Commentary="Test"/>
      </div>
    <Footer Footer_Title="Toast"/>

  </div>
</template>

<script>
import Historic from './Historic.vue'
import Footer from './Footer.vue'
import NavBar from './NavBar.vue';

export default {
  name: 'App',
  components: {
    Footer,
    Historic,
    NavBar
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
    .Historic_page {
        background-color: #6689E6;
        border-radius: 2px;
        padding: 10px;
        display: flex;
        flex-direction: column;
        margin: 20px;
        color: #F3F3F3;
        -webkit-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        -moz-box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
        box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 0.75);
    }
    .nav-section-title {
		text-decoration: none;
        position: relative; left: 160px;
        text-align: left;
		display: block;
		padding: 10px 10px 10px 20px;
		font-family: "Roboto", sans-serif;
		font-size: 65px;
		color: #91AFFF;
		margin: 5px 0;
		transition: all linear 250ms;
	}
</style>

<template>
  <div id="app">

    <Header/>
    <Home/>
    <HomeAbout/>
    <HomeDirections/>
    <HomeExpertise/>
    <HomeProjects/>
    <HomePartners/>
    <HomeContacts/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import HomeAbout from './components/HomeAbout.vue'
import HomeDirections from './components/HomeDirections.vue'
import HomeExpertise from './components/HomeExpertise.vue'
import HomeProjects from './components/HomeProjects.vue'
import HomePartners from './components/HomePartners.vue'
import HomeContacts from './components/HomeContacts.vue'
import Footer from './components/Footer.vue'



export default {
  name: 'App',
  components: {
    Header,
    Home,
    HomeAbout,
    HomeDirections,
    HomeExpertise,
    HomeProjects,
    HomePartners,
    HomeContacts,
    Footer
  }
}
</script>

<style>
#app {
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap');
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

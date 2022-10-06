<template>
 
   <NavBar />
   <HeroMe />
   <ExperienceMe />
   <FormMe /> 
   <FooterBar />

</template>

<script>
import FormMe from './components/FormMe.vue'
import NavBar from './components/NavBar.vue'
import FooterBar from './components/FooterBar.vue'
import HeroMe from './components/HeroMe.vue'
import ExperienceMe from './components/ExperienceMe.vue'


export default {
  name: 'App',
  components: {
    FormMe,
    NavBar,
    FooterBar,
    HeroMe,
    ExperienceMe
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

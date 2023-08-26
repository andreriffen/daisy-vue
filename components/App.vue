<template>
  
<div  id="global-div-wrapper" 
      class="bg-base-100 
             text-base-content 
             dark:bg-base-content 
             dark:text-base-200 
             scroll-smooth">
  
  <Navbar />
  <Main />
  <Footer />
  
</div>
</template>
  
<script>
import Navbar from '../components/Navbar.vue';
import Main from '../components/Main.vue';
import Footer from '../components/Footer.vue';
export default {
  name: "App",
  components: {Navbar, Main, Footer}
};
</script>
<style>
</style>
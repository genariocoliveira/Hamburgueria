<template>
  
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view/>

  <Footer />

</template>

<script>

import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Navbar,
    Footer
  },
  data() {
    return {
      logo_src: '/img/logo.png',
      app_name: 'Monte seu Hamburguer'
    }
  }
}

</script>

<style>
*{
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  box-sizing: border-box;
}
.main-container{
  margin: 50px;
  min-height: 300px;
}

h1{
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: #222;
}
</style>
<!-- Comando para iniciar o server backend = npm run backend -->
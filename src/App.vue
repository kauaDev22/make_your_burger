<template>
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view/>

  <Footer />
</template>

<script>

import Navbar from './components/NavBar.vue'
import Footer from './components/Footer.vue'
export default{
  name:'App',
  data(){},
  components:{
    Navbar,
    Footer
  },
  data(){
    return{
      logo_src : "img/logo.png",
      app_name: "Make your burguer"
    }
  }
}
</script>
<style>
  *{
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  

  h1{
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }
</style>

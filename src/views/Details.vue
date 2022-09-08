<template>
    <NavBar />
    <Details_body />
    <Footer />
  </template>
  
  <script>
  import NavBar from "../components/NavBar.vue"
  import Footer from "../components/Footer.vue"
  import Details_body from "../components/Details_compenents/Details_Body"

  export default {
  components:{
      NavBar,
      Details_body,
      Footer
  }
  }
  </script>
  
  <style>
  
  </style>
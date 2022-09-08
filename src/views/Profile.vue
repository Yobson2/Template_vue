<template>
    <NavBar />
    <Profile_Body />
    <Footer />
  </template>
  
  <script>
  import NavBar from "../components/NavBar.vue"
  import Footer from "../components/Footer.vue"
  import Profile_Body from "../components/Profile_Body.vue"
  export default {
  components:{
      NavBar,
      Footer,
      Profile_Body
  }
  }
  </script>
  
  <style>
  
  </style>
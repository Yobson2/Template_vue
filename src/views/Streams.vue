<template>
    <NavBar />
    <div class="container">
    <div class="row">
      <div class="col-lg-12">
        <div class="page-content">
         <div class="row">
          <div class="col-lg-8">
             <Streams1 />
             <Streams2 />

           </div>
          </div>
        </div>
      </div>
    </div>
  </div>
    <Footer />
  </template>
  
  <script>
  import NavBar from "../components/NavBar.vue"
  import Footer from "../components/Footer.vue"
  import Streams1 from "../components/Streams_components/Streams1.vue"
  import Streams2 from "../components/Streams_components/Streams2.vue"
  export default {
  components:{
      NavBar,
      Footer,
      Streams1,
      Streams2
      
  }
  }
  </script>
  
  <style>
  
  </style>
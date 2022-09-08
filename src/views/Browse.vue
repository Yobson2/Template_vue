<template>
  <NavBar />
  <div class="container">
    <div class="row">
      <div class="col-lg-12">
        <div class="page-content">
            <Browse_body1 />
            <Browse_body2 />

       </div>
      </div>
    </div>
  </div>
  <Footer />
</template>

<script>
import NavBar from "../components/NavBar.vue"
import Footer from "../components/Footer.vue"
import Browse_body1 from "../components/components_Browse/Browse_body1.vue"
import Browse_body2 from "../components/components_Browse/Browse_body2.vue"




export default {
components:{
    NavBar,
    Footer,
    Browse_body1,
    Browse_body2
}
}
</script>

<style>

</style>
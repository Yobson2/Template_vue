<template>
  <div class="home">
    <NavBar />
    <Home_body />
    <Footer />

  </div>
</template>

<script >
// @ is an alias to /src
import NavBar from '../components/NavBar.vue'
import Footer from '../components/Footer.vue'
import Home_body from '../components/Home_body.vue'




export default {
  name:"HelloWorld",
  components: {
    NavBar,
    Footer,
    Home_body
  }
}
</script>

<template>
    <header class="header-area header-sticky">
    <div class="container">
        <div class="row">
            <div class="col-12">
                <nav class="main-nav">
                    <!-- ***** Logo Start ***** -->
                    <router-link to="/index" class="logo">
                        <img src="../assets/images/logo.png" alt="">
                    </router-link>
                    <!-- ***** Logo End ***** -->
                    <!-- ***** Search End ***** -->
                    <div class="search-input">
                      <form id="search" action="#">
                        <input type="text" placeholder="Type Something" id='searchText' name="searchKeyword" onkeypress="handle" />
                        <i class="fa fa-search"></i>
                      </form>
                    </div>
                    <!-- ***** Search End ***** -->
                    <!-- ***** Menu Start ***** -->
                    <ul class="nav">
                        <li><router-link to="/" class="active">Home</router-link></li>
                        <li><router-link to="/Browse" >Browse</router-link></li>
                        <li><router-link to="/Details" >Details</router-link></li>
                        <li><router-link to="/Streams" >Streams</router-link></li>
                        <li><router-link to="/Profile" >Profile <img src="../assets/images/profile-header.jpg" alt=""></router-link></li>

                    </ul>  
                    <!-- <a class='menu-trigger'>
                        <span>Menu</span>
                    </a> -->
                    <!-- ***** Menu End ***** -->
                </nav>
            </div>
        </div>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style>

</style>
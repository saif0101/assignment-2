<script setup>
import Navbar from "./components/Home/navbar.vue"
import Header from "./components/Home/Header.vue"
import VaccineSlide from "./components/Home/VaccineSlide.vue"
import AllProducts from "./components/Home/Products.vue"
import AlsoLike from "./components/Home/AlsoLike.vue"
import Footer from "./components/Home/Footer.vue"
import Explore from "./components/Home/Explores.vue"
import Category from "./components/Home/Category.vue"
</script>

<template>
<div id="app">
  <Navbar/>
  <Header/>
  <VaccineSlide/>
  <Explore/>
  <AllProducts/>
  <Category/>
  <AlsoLike/>
  <Footer/>
</div>

</template>


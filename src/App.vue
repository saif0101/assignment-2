<script setup>
import Header from "./components/Home/Header.vue"
import AllProducts from "./components/Home/Products.vue"
import AlsoLike from "./components/Home/AlsoLike.vue"
import Footer from "./components/Home/Footer.vue"
import Explore from "./components/Home/Explores.vue"
import Category from "./components/Home/Category.vue"
</script>

<template>
<div id="app">
  <Header/>
  <Explore/>
  <AllProducts/>
  <Category/>
  <AlsoLike/>
  <Footer/>
</div>

</template>


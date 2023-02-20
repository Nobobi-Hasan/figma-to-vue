<template>

  <div class="container overflow-x-hidden">
    <NabbarVue />
    <Home />
    <Category />
    <TrickOrTreat />
    <Subscription />
    <Footer />
  </div>
  
</template>

<style scoped>

</style>

<script setup>
  import NabbarVue from './components/Navbar.vue'
  import Home from './components/Home.vue';
  import Category from './components/Category.vue';
  import TrickOrTreat from './components/TrickOrTreat.vue';
  import Subscription from './components/Subscription.vue';
  import Footer from './components/Footer.vue';
</script>

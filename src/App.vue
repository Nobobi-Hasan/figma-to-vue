<template>

  <div class="container overflow-x-hidden">
    <NabbarVue />
    <Home />
    <Category />
    <TrickOrTreat />
  </div>
  
</template>

<style scoped>

</style>

<script setup>
  import NabbarVue from './components/Navbar.vue'
  import Home from './components/Home.vue';
  import Category from './components/Category.vue';
  import TrickOrTreat from './components/TrickOrTreat.vue';
</script>

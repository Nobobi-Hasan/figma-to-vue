<template>

  <div class="container overflow-x-hidden">
    <NabbarVue />
    <Home />
    <Category />
  </div>
  
</template>

<style scoped>

</style>

<script setup>
  import NabbarVue from './components/Navbar.vue'
  import Home from './components/Home.vue';
  import Category from './components/Category.vue';
</script>

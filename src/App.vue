<script setup>
import HelloWorld from './components/HelloWorld.vue'
import MenuPrincipal from './components/Menu.vue'
import Footer from './components/Footer.vue';
</script>

<template>
  <div class="container-fluid">

    <MenuPrincipal/>
    <HelloWorld/>
    <Footer/>
  </div>
  
</template>

<style>
  body {
  background-color: #000000; /* Color gris claro */
}
</style>

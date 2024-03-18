<script setup>
import NavbarTop from './components/NavbarTop.vue';
import NavbarBot from './components/NavbarBottom.vue';
</script>


<template>
  <NavbarTop/>
  <router-view/>
  <NavbarBot/>
</template>

<style>
router-view {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
}
* {
  font-family: 'Kanit', sans-serif;
  margin: 0;
  padding: 0;
}


</style>

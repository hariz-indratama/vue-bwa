<script setup>
import { RouterView } from 'vue-router'
import NavBar from './components/layouts/NavBar.vue';

</script>

<template>
  <NavBar/>
  
  <RouterView />
</template>

<style>
@import "@/assets/css/styles.css"
</style>

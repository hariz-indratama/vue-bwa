<script setup>
import { RouterLink } from "vue-router";
import Logo from "./Logo.vue";
import NavigationLink from "./NavigationLink.vue";
import UserInfo from "./UserInfo.vue";

</script>

<template>
  <nav
    class="bg-white border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-800"
  >
    <div
      class="container flex flex-wrap items-center justify-between mx-auto my-2"
    >
    <Logo/>
    <NavigationLink/>
    <UserInfo/>
    
     
      
    </div>
  </nav>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import SiteNavBar from './components/SiteNavbar.vue'
import SiteFooter from './components/SiteFooter.vue'
</script>

<template>
  <div class="flex flex-col h-screen">
    <SiteNavBar/>
    <main class="flex-grow mt-20">
        <RouterView />
    </main>
    <SiteFooter/>
  </div>
</template>
<script setup>
import { RouterLink, RouterView } from 'vue-router'
import headerPage from '@/components/headerPage.vue'
import footerPage from './components/footerPage.vue';
// import mainPage from '@/views/menu.vue'
</script>

<template>
  
    <!-- <div class="navbar"> -->

      <headerPage />
      <RouterView />
      <footerPage />
      <RouterLink to="/main"> خانه </RouterLink>
      <RouterLink to="/home">درباره</RouterLink>
      <!-- <nav> 
      </nav>
    </div>

  <RouterView /> -->
</template>

<style scoped>

</style>

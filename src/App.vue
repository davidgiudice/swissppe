<template>
  <div class="container mx-auto p-4">
    <Header />
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
      <Sidebar />
      <MainContent />
    </div>
  </div>
</template>

<script setup>
import Header from './components/Header.vue';
import Sidebar from './components/Sidebar.vue';
import MainContent from './components/MainContent.vue';
</script>

<style scoped>
.container {
  max-width: 1200px;
}
</style>
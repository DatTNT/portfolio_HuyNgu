<script setup lang="ts">
import Header from '@/components/shared/Header-Datdev.vue'
import Home from '@/components/home/homeDat.vue'
</script>

<template>
  <div id="app">
    <Header></Header>
    <Home></Home>
  </div>
</template>

<style scoped>
header {
  margin-bottom: 10px;
  margin-top: 20px;
  display: flex;
  align-items: center;
}
</style>

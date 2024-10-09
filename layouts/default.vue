<!-- layouts/default.vue -->
<template>
    <div>
      <!-- TheHeader will be included on all pages using this layout -->
      <TheHeader class="shadow-md" />
  
      <!-- Page content will be rendered here -->
      <NuxtPage />
    </div>
  </template>
  
  <script setup>
  import TheHeader from '~/components/TheHeader.vue';
  </script>
  
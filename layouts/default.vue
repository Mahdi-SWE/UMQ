<!-- layouts/default.vue -->
<template>
  <div class="flex flex-col min-h-screen">
    <!-- TheHeader Component (Appears on all pages) -->
    <TheHeader />

    <!-- Main Page Content -->
    <div class="flex-grow">
      <NuxtPage />
    </div>

    <!-- TheFooter Component (Appears on all pages) -->
    <TheFooter />
  </div>
</template>

<script setup>
import TheHeader from '~/components/TheHeader.vue';
import TheFooter from '~/components/TheFooter.vue';
</script>

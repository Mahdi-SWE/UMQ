<script setup>
import { createClient } from '@supabase/supabase-js'
const supabase = createClient('https://tcyirnghbyqsfezcimop.supabase.co', 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InRjeWlybmdoYnlxc2ZlemNpbW9wIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MjA3MDI2MjMsImV4cCI6MjAzNjI3ODYyM30.rw0g0U7TLk_x6lyOjw0BWhZXJdz5aVrPTgqU0qi-AJU')
const countries = ref([])

async function getCountries() {
  const { data } = await supabase.from('countries').select()
  countries.value = data
}

onMounted(() => {
  getCountries()
})
</script>

<template>
  <ul>
    <li v-for="country in countries" :key="country.id">{{ country.name }}</li>
  </ul>
</template>
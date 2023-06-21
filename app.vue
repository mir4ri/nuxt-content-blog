<!-- ./app.vue -->
<script setup>
useHead({
  title: "Вільний простір",
  meta: [
    { name: 'description', content: 'Блог написаний на Nuxt 3' }
  ],
})
</script>
<template>
  <div>
    <SiteHeader />
    <NuxtPage />
  </div>
</template>

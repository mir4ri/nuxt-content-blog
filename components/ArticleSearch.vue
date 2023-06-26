<!-- ./components/Search.vue -->

<script setup>
  let search = '';
</script>

<template>
  <div class="search">
    <input
      type="text"
      placeholder="Пошук"
      class="search-input"
      @input="search"
    />
  </div>
</template>

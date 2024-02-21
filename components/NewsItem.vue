<template>
  <div class="card">
    <p>{{ newsItem.title }}</p>
    <NuxtLink :to="`/news/${newsItem.id}`">
      <p>view details</p>
    </NuxtLink>
  </div>
</template>

<script setup>
  const { newsItem } = defineProps(['newsItem'])

</script>

<style scoped>

</style>
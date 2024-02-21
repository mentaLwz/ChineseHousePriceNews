<template>
  <div>
    <div class="grid grid-cols-12 gap-2">
      <div v-for="item in newsItems">
        <NewsItem :newsItem="item" />

      </div>
    </div>
  </div>
</template>

<script setup>
  const { data: newsItems } = await useFetch('http://localhost:5000/posts')
</script>

<style scoped>

</style>
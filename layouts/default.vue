<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container text-lg mx-auto p-4 flex justify-between">
        <NuxtLink to="/">中国房价信息汇总</NuxtLink>
        <ul class="flex gap-4">
          <li><NuxtLink to="/about">关于</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <div class="container mx-auto p-4">
      <slot ></slot>
    </div>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
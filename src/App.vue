<template>
  <div class="flex h-lvh">
    <div class="w-40 p-5 bg-gray-100">
      <h1 class="mb-3 text-lg font-bold text-blue-600">Vite + Vue.js + tailwindCSS</h1>
      <router-link to="/" class="block mb-3 no-underline hover:underline">Home</router-link>
      <router-link to="/about" class="block mb-3 no-underline hover:underline">About</router-link>
    </div>

    <router-view class="p-5"/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>
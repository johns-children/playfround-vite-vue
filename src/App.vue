<template>
  <div>
    <h1>Vite + Vue.js + tailwindCSS</h1>
    <div>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>

    <router-view class="main flex-item"/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>
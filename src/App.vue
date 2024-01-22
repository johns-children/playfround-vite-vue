<template>
  <div id="app">
    <div id="sidebar">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>

    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  display: flex;
}

#sidebar {
  width: 200px;
  padding: 20px;
  background-color: #f0f0f0;
}

#sidebar a {
  display: block;
  margin-bottom: 10px;
  color: #333;
  text-decoration: none;
}

#sidebar a:hover {
  text-decoration: underline;
}
</style>

<template>
  <div id="app">
    <div id="sidebar">
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

<style>
#app {
  height: 100vh;
  display: flex;
}

#sidebar {
  width: 100px;
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

.main {
  padding: 20px
}

.flex-item {
  flex: 1
}
</style>

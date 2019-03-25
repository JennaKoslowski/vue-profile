<template>
<div class="container">
    <nav class="navbar">
        <nuxt-link class="navbar-item" to="/">Home</nuxt-link>
        <nuxt-link class="navbar-item" to="/about">About</nuxt-link>
        <nuxt-link class="navbar-item" to="/blog">Blog</nuxt-link>
        <nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
        <nuxt-link class="navbar-item" to="/contact">Contact</nuxt-link>
    </nav>
</div>
</template>


<style scoped>
    .container {
      display: flex;
      justify-content: flex-end;
      height: 100vh;
      width: 10vw;
    }
  .navbar {
      background-color: #ad70e0;
      color: black;
      text-decoration: underline; 
      height: 100vh;
      width: 10vw;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
  }
</style>

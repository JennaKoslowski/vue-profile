<template>
<div class="container">
    <nav class="navbar">
        <ul>
        <li><nuxt-link class="navbar-item" to="/">Home</nuxt-link></li>
        <li><nuxt-link class="navbar-item" to="/about">About</nuxt-link></li>
        <li><nuxt-link class="navbar-item" to="/blog">Blog</nuxt-link></li>
        <li><nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link></li>        
        <li><nuxt-link class="navbar-item" to="/contact">Contact</nuxt-link></li>
        </ul>
    </nav>
</div>
</template>


<style scoped>
    .container {
      background-color: #ad70e0;
      color: black;
      text-decoration: underline; 
      height: 100vh;
      width: 25vw;
      
    }
  
</style>

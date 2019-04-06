<template>
<div class="sideContainer">
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
    .sideContainer {
      background-color: #4c535e;
      color: white;
    }
</style>

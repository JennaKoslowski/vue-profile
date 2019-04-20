<template>
<div class="sideContainer">
    <nav class="navBar">
        <ul class="navList">
        <li><nuxt-link class="navbar-item links" to="/">Home</nuxt-link></li>
        <li><nuxt-link class="navbar-item links " to="/about">About</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/blog">Blog</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/projects">Projects</nuxt-link></li>        
        </ul>
    </nav>
</div>
</template>


<style scoped>
    .sideContainer {
      background-color: #788291;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: space-around;
      height: 100vh;
    }
    .navList {
        list-style-type: none;
    }
    
</style>

<template>
<div class="sideContainer">
    <nav class="navBar">
        <ul class="navList">
        <li><nuxt-link class="navbar-item links" to="/">Home</nuxt-link></li>
        <li><nuxt-link class="navbar-item links " to="/about">About</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/blog">Blog</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/projects">Projects</nuxt-link></li>        
        <li><a href="https://github.com/JennaKoslowski" class= "links">GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/jennakoslowski/" class="links">LinkedIn</a></li>
        </ul>
    </nav>
</div>
</template>

<style scoped>
    .sideContainer {
      background-color: var(--midnight);
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      padding-top: 50%
    }
    .navList {
        list-style-type: none;
        position:fixed;
    }
    
</style>

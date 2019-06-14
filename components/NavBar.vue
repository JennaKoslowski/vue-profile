<template>
<Slide right>
<div class="sideContainer">
    <nav class="navBar">
        <ul class="navList">
        <li><span class="navbar-item links" to="/">Home</span></li>
        <li><span class="navbar-item links " to="/about">About</span></li>
        <li><span class="navbar-item links" to="/blog">Blog</span></li>
        <li><span class="navbar-item links" to="/projects">Projects</span></li>        
        <li><a href="https://github.com/JennaKoslowski" target="_blank" class= "links">GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/jennakoslowski/" target="_blank" class="links">LinkedIn</a></li>
        </ul>
    </nav>
</div>
</Slide>
</template>

<script>
import  Slide  from 'vue-burger-menu'

export default {
    components: {
    Slide
    }
}
</script>


<style scoped>
    .sideContainer {
      background-color: var(--midnight);
      display: flex;
      flex-direction: column;
      justify-content: center;
      border-radius: 50% 0px 0px 50%;
      height: 100vh;
      width: 20%;
      position:fixed;
      bottom: 0;
      right: 0;
    }
    .navList {
        list-style-type: none;
        position:fixed;
        background:var(--midnight);
        transform:translate(6%,-50%);
    }
    .links , li{
        background: var(--midnight);
    }
</style>

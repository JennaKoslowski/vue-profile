<template>
<div>
  <font-awesome-icon :icon="['fas', 'bars']" class="font"/>
<div class="sideContainer">
    <nav class="navBar">
        <ul class="navList">
        <li><nuxt-link class="navbar-item links" to="/">Home</nuxt-link></li>
        <li><nuxt-link class="navbar-item links " to="/about">About</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/blog">Blog</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/projects">Projects</nuxt-link></li>        
        <li><a href="https://github.com/JennaKoslowski" target="_blank" class= "links">GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/jennakoslowski/" target="_blank" class="links">LinkedIn</a></li>
        </ul>
    </nav>
</div>
</div>
</template>

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
    .font{
      display:none;
    }
    
@media only screen and (max-width: 612px) {
    .font{
      color: var(--midnight);
      height: 10vh;
      width: 10vw;
      font-size:20px;
      display:block; 
  }
 .sideContainer{
    display: none;
  }
  
}
</style>

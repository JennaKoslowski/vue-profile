<template>
<div class="sideContainer" >
    <nav class="navBar">
        <ul class="navList">
        <li><nuxt-link class="navbar-item links" to="/"><fas :icon="['fas', 'home']" class="navFont"/>Home</nuxt-link></li>
        <li><nuxt-link class="navbar-item links " to="/about"><fas :icon="['fas', 'user-circle']" class="navFont"/>About</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/blog"><fas :icon="['fas', 'pen-square']" class="navFont"/>Blog</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/projects"><fas :icon="['fas', 'laptop-code']" class="navFont"/>Projects</nuxt-link></li>        
        <li><a href="https://github.com/JennaKoslowski" target="_blank" class= "links">GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/jennakoslowski/" target="_blank" class="links">LinkedIn</a></li>
        </ul>
    </nav>
</div>
</template>
<script>
  import { fas } from '@fortawesome/free-solid-svg-icons'
  export default {
    computed: {
      fas () {
         return fas
      },
    },
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
      width: 30vw;
      position:fixed;
      bottom: 0;
      right: 0;
    }
    .navFont{
      color: var(--lavender);
      height: 30px;
      background-color: var(--midnight);
      font-size:20px;
      margin: 5px;
    }
    .navList {
        list-style-type: none;
        position:fixed;
        width:30%;
        background:var(--midnight);
        transform:translate(6%,-50%);
    }
    .links , li{
        background: var(--midnight);
    }
@media only screen and (max-width: 612px) {
  
 .sideContainer{
    display: none;
  }
  
}
</style>

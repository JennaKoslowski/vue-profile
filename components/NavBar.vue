<template>
<div class="sideContainer" >
    <nav class="navBar">
        <ul class="navList">
        <li><nuxt-link class="navbar-item links" to="/">Home</nuxt-link></li>
        <li><nuxt-link class="navbar-item links " to="/about">About</nuxt-link></li>
        <li><nuxt-link class="navbar-item links" to="/projects">Projects</nuxt-link></li>
        <li><a href="https://jkimexploring.wordpress.com/coding/" target="_blank" class= "links">Blog</a></li>        
        <li><a href="https://github.com/JennaKoslowski" target="_blank" class= "links offSite">GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/jennakoslowski/" target="_blank" class="links offSite">LinkedIn</a></li>
        </ul>
    </nav>
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
      width: 30vw;
      position:fixed;
      bottom: 0;
      right: 0;
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
 @media only screen and (max-width: 469px) {
 .sideContainer{
      background-color: var(--midnight);
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: center;
      border-radius: 0px;
      height: 10vh;
      width: 100vw;
      position:fixed;
      top: 0;
      left: 0;
  }
   .navList {
      list-style-type: none;  
      top:0;
      left: 0;
      width:100%;
      background:var(--midnight);
      display:flex;
      flex-wrap: wrap;
      margin: 0;
      padding: 0;
    }
    .links{
      padding: 5vw;
      display: flex;
      flex-direction: row;
      flex-wrap: nowrap;
      align-items: center;
      justify-content: center;
      text-align: center;
      font-size: 16px;
      margin-top: 10vh
    }
    .offSite{
      display: none;
    }
}
</style>

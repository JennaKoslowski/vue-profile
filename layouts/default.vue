<template>
   <div id= "navandcontent">
    <nuxt class="nuxt"/>
    <NavBar class="nav"/>
    </div>
</template>

<script>
  import NavBar from '@/components/NavBar'

  export default {
    components: {
      NavBar
    }
  }
</script>

<style>
  #navandcontent{
    display:flex;
  }
    .nuxt{
    margin-top: 12vh;
    padding-left: 10px
  }

 @media only screen and (min-width: 469px){
  #navandcontent {
  display: grid;
  grid-template-columns: 4fr 1fr;
}

 }
</style>

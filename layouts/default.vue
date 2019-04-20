<template>
   <div id= "navandcontent">
    <nuxt />
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
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 18px;
  word-spacing: 3px;
  line-height: 2;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: whitesmoke;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

#navandcontent {
  display: grid;
  grid-template-columns: 4fr 1fr;
}
</style>

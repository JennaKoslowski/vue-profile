<template>
<nuxt-link :to="'/blog/' + id">
  <article class="posts"> 
    <h1>{{ title }}</h1>
    <p class= "previewText">{{ previewText }}</p>
  </article> </nuxt-link>
</template>

<script>
    export default {
        props: ['title', 'previewText', 'id']
    }
</script>

<style scoped>
    .posts {
      background-color: var(--middle);
      color: var(--koa);
    }
    .previewText {
      text-decoration: none;
    }
   
</style>
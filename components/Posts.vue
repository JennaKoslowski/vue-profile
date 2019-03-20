<template>
<nuxt-link :to="'/blog/' + id">
  
  <article class="posts"> 
    <h1>{{ title }}</h1>
    <p>{{ previewText }}</p>
  </article> </nuxt-link>
</template>

<script>
    export default {
        props: ['title', 'previewText', 'id']
    }
</script>

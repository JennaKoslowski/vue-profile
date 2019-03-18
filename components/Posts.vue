<template>
  <article class="posts"> 
    <h1>{{ title }}</h1>
    <p>{{ previewText }}</p>
  </article>
</template>

<script>
    export default {
        props: ['title', 'previewText']
    }
</script>

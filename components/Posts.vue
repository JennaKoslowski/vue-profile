<template>
    <div>
  <article class="posts"> 
    <h1>{{ title }}</h1>
    <p>{{ previewText }}</p>
  </article>
</div>
</template>

<script>
    export default {
        props: ['title', 'previewText']
    }
</script>

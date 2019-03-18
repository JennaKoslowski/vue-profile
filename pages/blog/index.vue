<template>

    <section class="blog">

        <Posts class="post"
            title="Building with Nuxt" 
            previewText="This is my first try with nuxt.js and vue. Let's see how it goes." />

    </section>

</template>

<script>
    import Posts from '@/components/Posts'

    export default {
        components: {
            Posts
        }
    }
</script>

<style scoped>
    .blog {
        background: black;
    }
    .post {
        color: white;
        padding: 10px;
        height: 150px;
        border: 1px solid #ccc;
    
    }
    .post h1 {
        color: #7cdcff;
        display: flex;
        justify-content: center;
    }
</style>
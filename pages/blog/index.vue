<template>

    <section class="blog">
        <h1 class= "title">
        Blog
    </h1>
        <Posts class="post" id="2"
            title="Building with Nuxt" 
            previewText="This is my first try with nuxt.js and vue. Let's see how it goes." />
        <Posts class="post" id="1"
            title="How to create your first commit on GitHub" 
            previewText="Learn how to get your project to show up as a new repository on GitHub." />
    </section>

</template>

<script>
    import Posts from '@/components/Posts'

    export default {
        components: {
            Posts
        },
    }
</script>

<style scoped>
    .blog {
        background-color: whitesmoke;
        color: #4c535e;
        padding: 40px 15px;
    }
    .post {
        color: #4c535e;
        padding: 10px;
        height: 150px;
    }
    .post h1 {
        color: #4c535e;
        display: flex;
        justify-content: center;
    }
</style>
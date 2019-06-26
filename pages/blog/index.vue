<template>

    <section class="blog">
        <h1 class= "title">
            Blog
        </h1>
        <nuxt-link v-for="post in posts"
            :key="post.id"
            :to="post.id"></nuxt-link>
    </section>

</template>

<script>
    import Posts from '@/components/Posts'

    export default {
        components: {
            Posts
        },
        asyncData(){
            return context.app.$storyapi.get('cdn/stories/blog', {
                version: 'draft'
            }).then(res=>{
                console.log(res);
                return res;
            });
        }
    }
</script>

<style scoped>
    .blog {
        background: var(--middle);
        color: var(--koa);
        padding: 40px 15px;
    }
    .post {
        background: var(--middle);
        color: var(--koa);
        padding: 10px;
        height: 150px;
    }
    .post h1 {
        color: var(--koa);
        display: flex;
        justify-content: center;
    }
</style>
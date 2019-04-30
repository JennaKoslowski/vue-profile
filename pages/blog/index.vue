<template>

    <section class="blog">
        <h1 class= "title">
        Blog
    </h1>
        <Posts class="post" id="5"
            title="Creating with Vue.js and Nuxt.js: The static sidebars"
            previewText="The past week or so I started to create the sidebars for my profile. Right now I'm mainly working on getting all the information done and looking semi-decent. " />
        <Posts class="post" id="4"
            title="Creating with Vue.js and Nuxt.js: Initial reaction"
            previewText="When I decided to create a personal portfolio website I spent probably more time than I needed to watching YouTube videos to decide whether I should attempt React, Angular or Vue." />
        <Posts class="post" id="3"
            title="My Udacity Nanodegree story"
            previewText="Basically this wasn’t a snap second decision. I knew this was a new(ish) thing I wanted to learn and pursue." />   
        <Posts class="post" id="2"
            title="So you want to learn how to code" 
            previewText="I did go through one program completely there are plenty of other resources I used to supplement that learning as well as programs I went through before and some I plan to do coming up." />
        <Posts class="post" id="1"
            title="Phase one recap: Google developer challenge scholarship" 
            previewText="I was accepted into phase two of the Google Developer Challenge Scholarship so I decided to talk about how I got into phase two and some tips for people who are learning coding." />
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
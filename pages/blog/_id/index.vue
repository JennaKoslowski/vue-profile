<template>
    <section class="single-blog">
        <h1>{{ $route.params.id}}</h1>
        <h3> By: Jenna Koslowski</h3>
        <p>Blog article here.</p>
        <p>Follow me on my social media: 
            <a href="https://github.com/JennaKoslowski">GitHub</a>, 
        <a href="https://www.linkedin.com/in/jennakoslowski/">LinkedIn</a>, 
        <a href="https://twitter.com/JennaKoslowski">Twitter</a>, and
        <a href="https://www.instagram.com/jenna.koslowski/">Instagram</a>
        </p>
    </section>
</template>

<style scoped>
    body {
        background-color: whitesmoke;
        color: #4c535e;
    }
    .single-blog {
        display:flex;
        flex-flow: column;
        justify-content: center;
        text-align: center;
        padding: 20px;
    }
</style>
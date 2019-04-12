<template>
    <section class="single-blog">
        <h1>{{ $route.params.id}}</h1>
        <h3> By: Jenna Koslowski</h3>
        <p>Blog article here.</p>
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
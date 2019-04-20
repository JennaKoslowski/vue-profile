<template>
<section>
<div class="projects"> 
    <h1>{{ title }}</h1>
    <img :src="screenshot" class= "images"/>
    <p>{{languages}}</p>
    <a :href="github"><button>Github</button></a>
</div>
</section>
</template>

<script>
    export default {
        props: ['title', 'languages', 'screenshot']
    }
</script>

<style scoped>
.images{
    height:150px;
}

</style>
<template>
<section>
<div class="projects"> 
    <h1>{{ title }}</h1>
    <img :src="screenshot" class= "images"/>
    <p>{{languages}}</p>
    <a :href="github" target="_blank"><button>Github</button></a>
</div>
</section>
</template>

<script>
    export default {
        props: ['title', 'languages', 'screenshot', 'github']
    }
</script>

<style scoped>
.images{
   width:300px;
}

</style>
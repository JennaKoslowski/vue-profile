<template>
<section>
<div class="projects"> 
    <h1>{{ title }}</h1>
    <img :src='screenshot' class= "images"/>
    <!--<button>github</button> how to get link to change for each element-->
    <p>{{languages}}</p>
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
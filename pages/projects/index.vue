<template>
<section>
    <h1 class= "title">
        Projects
    </h1>
    <div class="projectblock">
    <h2> Current Projects </h2>
    <section class="currentprojects">
        <Projects class="projects"
            title="Coffee Map"
            languages= "HTML, CSS, JS, React.JS"
            screenshot= "../../coffeeMap.JPG"
            github= 'https://github.com/JennaKoslowski/neighborhood-maps' />
        <Projects class="projects"
            title="Vue Profile"
            languages= "HTML, CSS, JS, Vue.JS, Nuxt.JS"
            screenshot="../../vueProfile.JPG"
            github= "https://github.com/JennaKoslowski/vue-profile" />   
    </section>
    <h2>Completed Projects</h2>
    <section class="completedprojects"> 
        <Projects class="projects"
            title="MyReads"
            languages= "HTML, CSS, JS, React.JS"
            screenshot="../../myReads.JPG"
            github= "https://github.com/JennaKoslowski/react-myreads" />
        <Projects class="projects"
            title="Arcade Game"
            languages= "HTML, CSS, JS"
            screenshot="../../arcadeGame.JPG"
            github="https://github.com/JennaKoslowski/frontend-nanodegree-arcade-game" />
        <Projects class="projects"
            title="Memory Game"
            languages= "HTML, CSS, JS"
            screenshot="../../matchingGame.JPG"
            github= "https://github.com/JennaKoslowski/fend-memory-project" />
    </section>           
    </div>
</section>
</template>

<script>
    import Projects from '@/components/Projects'

    export default {
        components: {
            Projects
        }
    }
</script>

<style scoped>
.projectblock {
    width: 90%;
    margin: auto;
}
section {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    }
.projects {
    margin: 10px;
    padding: 10px;
    color: var(--koa);
}
</style>
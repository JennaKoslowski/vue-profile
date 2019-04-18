<template>
<section>
    <h1 class= "title">
        Projects
    </h1>
    <div class="projectblock">
    <h2> Current Projects </h2>
            <Projects class="projects"
            title="Coffee Map"
            languages= "HTML, CSS, JS, ReactJS"
            github= "https://github.com/JennaKoslowski/neighborhood-maps" />
            <Projects class="projects"
            title="Vue Profile"
            languages= "HTML, CSS, JS, VueJS"
            github= "https://github.com/JennaKoslowski/vue-profile" />
    <h2>Completed Projects</h2>
        <Projects class="projects"
            title="Arcade Game"
            languages= "HTML, CSS, JS"
            github= "https://github.com/JennaKoslowski/frontend-nanodegree-arcade-game" />
        <Projects class="projects"
            title="MyReads"
            languages= "HTML, CSS, JS, ReactJS"
            github= "https://github.com/JennaKoslowski/react-myreads" />
        <Projects class="projects"
            title="Memory Game"
            languages= "HTML, CSS, JS"
            github= "https://github.com/JennaKoslowski/fend-memory-project" />
           
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
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  text-align: center;
  font-weight: 300;
  font-size: 100px;
  color: #4c535e;
  letter-spacing: 1px;
}
.projectblock {
    width: 90%;
    height: 50vh;
    margin: auto;
    border: 1px solid #4c535e;
}
.projects {
    width: 25%;
    height:25%;
    border: 1px solid #4c535e;
    margin: auto;
}
</style>
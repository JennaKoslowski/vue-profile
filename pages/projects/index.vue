<template>
<section>
    <h1 class= "title">
        Projects
    </h1>
    <div class="projectblock">
        <Projects class="projects"
            title="Arcade Game"
            languages= "HTML, CSS, JS"
            github= "https://github.com/JennaKoslowski/frontend-nanodegree-arcade-game" />
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
</style>
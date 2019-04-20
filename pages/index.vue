<template>
  <section class="container">
    <div>
      <h1 class="title">
        Jenna Koslowski
      </h1>
      <h2 class="subtitle">
        JavaScript Developer
      </h2>
      <a href="https://github.com/JennaKoslowski/"><button>Github</button></a>
      <a href="https://www.linkedin.com/in/jennakoslowski/"><button>LinkedIn</button></a>
      <h4 class="construction">
        *This site is currently under construction. 
      </h4>
    </div>
  </section>
</template>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
* {
  color: #4c535e;
  background-color: whitesmoke;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #4c535e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #4c535e;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.construction{
  bottom: 0;
  left: 0;
  position: absolute;
}
</style>

<style>
.links {
  padding-top: 15px;
  color:whitesmoke;
}
.links:visited {
color:whitesmoke;
}

button{
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #4c535e;
  color: #4c535e;
  text-decoration: none;
  padding: 10px 30px;
}

button:hover {
  border: 2px solid #4c535e;
  color: #4c535e;
}
</style>

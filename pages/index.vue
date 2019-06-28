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
  color: var(--koa);
  background-color: var(--middle);
}
.subtitle {
  font-weight: 300;
  color: var(--koa);
  word-spacing: 5px;
  padding-bottom: 15px;
}
</style>


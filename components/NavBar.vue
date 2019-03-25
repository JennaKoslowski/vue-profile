<template>
<div class="container">
    <nav class="navbar">
        <nuxt-link class="navbar-item" to="/">Home</nuxt-link>
          <nuxt-link class="navbar-item" to="/about">About</nuxt-link>
          <nuxt-link class="navbar-item" to="/blog">Blog</nuxt-link>
          <nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
          <nuxt-link class="navbar-item" to="/contact">Contact</nuxt-link>
    </nav>
</div>
</template>

<script>
import NavBar from '../comoponents/NavBar'

export default {
    components: {
        NavBar
    }
}
</script>
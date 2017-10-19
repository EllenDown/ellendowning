<template>
  <div class="mainNav">
    <nav class="navbar container">
        <div class="navbar-brand">
          <a href="#" class="navbar-item column">
            <div class="name">
              <h1 class="logo">Ellen Louise Downing</h1>
            </div>
            <div class="tagline">
              <p>Creation Via Elagantly Crafted Code</p>
            </div>
          </a>
          </div>
            <div class="navbar-end">
              <a class="navbar-item" @click.prevent="jump('#about')">About</a>
              <a class="navbar-item" @click.prevent="jump('#portfolio')">Portfolio</a>
              <a class="navbar-item" @click.prevent="jump('#contact')">Contact</a>
            </div>
    </nav>
  </div>

</template>

<script>

import jump from 'jump.js'

export default {
  name: 'mainNav',
  
}
</script>

<style scoped>

nav {
  margin-bottom: 5%;
}

.navbar {
  font-family: 'Codystar', cursive;
  background-color: white;
  font-weight: bolder;
}

h1 {
  font-size: 3rem;
}

.tagline {
  font-size: 1.2rem;
  font-family: 'Unica One', cursive;
  letter-spacing: .3rem;
}

</style>

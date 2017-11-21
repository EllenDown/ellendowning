<template>
  <div class="mainNav">
    <nav class="navbar">
        <div class="navbar-brand">
          <div class="navbar-item column">
            <div class="name">
              <h1 class="logo">Ellen Louise Downing</h1>
            </div>
            <div class="tagline">
              <p>Creation Via Elagantly Crafted Code</p>
            </div>
          </div>
          </div>
            <div class="navbar-end">
              <a class="navbar-item" @click.prevent="jump('#about')">About</a>
              <a class="navbar-item" @click.prevent="jump('#portfolio', {offset: -40})">Portfolio</a>
              <a class="navbar-item" @click.prevent="jump('#contact', {offset: -40})">Contact</a>
            </div>
    </nav>
  </div>

</template>

<script>

import jump from 'jump.js'

export default {
  name: 'mainNav',
  data() {
    return {
      mobile: false,
      jump: jump
    }
  }
}

</script>

<style scoped>

nav {
  margin-bottom:2rem;;
}

.navbar {
  font-family: 'Poiret One', cursive;
  background-color: white;
  font-weight: bolder;
  margin-left: 2rem;
  margin-right: 2rem;
}

h1 {
  font-size: 4rem;
  text-transform: uppercase;
  letter-spacing: .2rem;
}

a {
  font-size: 1rem;
  text-transform: uppercase;
  letter-spacing: .2rem;
}


.tagline {
  font-size: 1.2rem;
  font-family: 'Unica One', cursive;
  letter-spacing: .3rem;
}

</style>

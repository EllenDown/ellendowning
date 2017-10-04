<template>
  <div class="mainNav">
    <nav class="navbar container">
        <div class="navbar-brand">
          <router-link to="/" class="navbar-item column">
            <div class="name">
              <h1 class="logo">Ellen Louise Downing</h1>
            </div>
            <div class="tagline">
              <p>Creation Via Elagantly Crafted Code</p>
            </div>
          </router-link>
          </div>
            <div class="navbar-end">
              <router-link to='/about' class="navbar-item">About</router-link>
              <router-link to='/portfolio' class="navbar-item">Portfolio</router-link>
              <router-link to='/contact' class="navbar-item">Contact</router-link>
            </div>
    </nav>
  </div>

</template>

<script>
export default {
  name: 'mainNav'
}
</script>

<style scoped>

.navbar-brand {
  margin-bottom: 20px;
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

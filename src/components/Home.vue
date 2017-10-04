<template>
  <div class="home">
    <mainNav></mainNav>
    <div class="columns">
      <div class="column">
        <about></about>
        <img class="grayscale run" src="../assets/RunImage.jpg">
        <contact></contact>
      </div>
      <div class="main column">
        <img class="grayscale headshot" src="../assets/FaceImage.jpg">
        <portfolio></portfolio>
      </div>
    </div>
    <bottom></bottom>
  </div>
</template>

<script>

import MainNav from './MainNav.vue'
import About from './About.vue'
import FaceImage from '../assets/FaceImage.jpg'
import RunImage from '../assets/RunImage.jpg'
import Portfolio from './Portfolio.vue'
import Contact from './Contact.vue'
import Bottom from './Bottom.vue'

export default {
  name: 'home',
  components: {
    MainNav,
    About,
    Portfolio,
    Contact,
    Bottom
  }
}
</script>

<style scoped>

img {
  width: 90%;
  margin: auto;
  margin-top: 12%;
}

img.headshot {
  height: 100vh;
}

img.run {
  width: 90%;
  margin-left: 5%;
  margin-top: 12%;
  height: 100vh;
}

img.grayscale {
  filter: url("data:image/svg+xml;utf8,<svg xmlns=\'../assets/FaceImage.jpg'\><filter id=\'grayscale\'><feColorMatrix type=\'matrix\' values=\'0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0 0 0 1 0\'/></filter></svg>#grayscale");
  filter: gray;
  -webkit-filter: grayscale(100%);
  -webkit-transition: all .6s ease;
  -webkit-backface-visibility: hidden;
}

img.grayscale:hover {
  filter: none;
  -webkit-filter: grayscale(0%);
}

</style>

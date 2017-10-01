<template>
  <div class="home columns">
    <div class="column">
      <mainNav></mainNav>
      <about></about>
      <portfolio></portfolio>
      <contact></contact>
    </div>
    <div class="main hero column">
      <img class="grayscale" src="../assets/FaceImage.jpg">
      <div class="me">
        <h2 class="me">Me:</h2>
      </div>
      <div class="mtn">
        <h2 class="mtn">MOUNTAIN TRAILS</h2>
      </div>
      <div class="run">
        <h2 class="run">running shoes</h2>
      </div>
      <div class="change">
        <h2 class="change">InnoVATIVE CHANGE</h2>
      </div>
      <div class="mallow">
        <h2 class="mallow">MARSHMALLOWS</h2>
      </div>
      <div class="silence">
        <h2 class="silence">colorful silence</h2>
      </div>
      <div class="evolution">
        <h2 class="evolution">EVOLUTION</h2>
      </div>
      <div class="slow">
        <h2 class="slow">SLOWING down</h2>
      </div>
      <div class="edible">
        <h2 class="edible">Edible Experiences</h2>
      </div>
      <div class="sleep">
        <h2 class="sleep">Sleeping With Dreams</h2>
      </div>
      <div class="simple">
        <h2 class="simple">Simple Love</h2>
      </div>
    </div>
  </div>
</template>

<script>

import MainNav from './MainNav.vue'
import About from './About.vue'
import FaceImage from '../assets/FaceImage.jpg'
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

.home {
  background-color: white;
}

img {
  width: 50%;
  height: 100vh;
  position: fixed;
  top: 0;
  right: 0;
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

h2 {
  position: absolute;
  font-family: 'Overlock', cursive;
  color: white;
  right: 20px;
}

.me {
  font-size: 3rem;
  top: 15%;
}

.mtn {
  top: 25%;
  font-size: 1.3rem;
}

.run {
  top: 30%;
  font-size: 1.4rem;
}

.mallow {
  top: 34%;
  font-size: 1.1rem;
  font-weight: bolder;
}

.sleep {
  top: 36%;
  font-size: .9rem;
  line-height: 2rem;
}

.silence {
  top: 48%;
  font-size: 1.5rem;
}

.edible {
  top: 44%;
  font-size: 1.1rem;
  font-weight: bolder;
}

.change {
  top: 62%;
  font-size: 1.5rem;
  font-weight: bolder;
}

.slow {
  top: 55%;
  line-height: 3rem;

}

.evolution {
  top: 39%;
  font-weight: bolder;
  line-height: 3rem;
  letter-spacing: .4rem;
}

.simple {
  top: 52%;
  line-height: 1.6rem;
  font-size: 1.6rem;
}


</style>

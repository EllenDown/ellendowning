<template>
  <div class="portfolio">
    <h3>Portfolio:</h3>
      <img class="grayscale" src="../assets/FeestLand.jpg">
      <img class="grayscale" src="../assets/ThymeShareLand.jpg">
      <img class="grayscale" src="../assets/cityBlockWide.jpg">
      <img class="grayscale" src="../assets/MagpieImage.png">

    </div>
</template>

<script>

import FeestLand from '../assets/FeestLand.jpg'
import cityBlockWide from '../assets/cityBlockWide.jpg'
import ThymeShareLand from '../assets/ThymeShareLand.jpg'
import MagpieImage from '../assets/MagpieImage.png'

export default {
  name: 'portfolio',
}
</script>

<style scoped>

.portfolio {
  margin-top: 5%;
  margin-bottom: 30px;
}

img {
  width: 90%;
  margin: auto;
  height: 35vh;
}

img.grayscale {
    filter: gray;
    -webkit-filter: grayscale(100%);
    -webkit-transition: all .6s ease;
    -webkit-backface-visibility: hidden;
  }

  img.grayscale:hover {
    filter: none;
    -webkit-filter: grayscale(0%);
  }

  h3 {
    font-size: 2rem;
    font-family: 'Unica One', cursive;
    border-left: thick solid black;
    padding-left: 20px;
    margin-bottom: 5%;
  }

</style>

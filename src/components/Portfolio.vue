<template>
  <div id="portfolio" class="portfolio">
    <h3>Portfolio:</h3>
      <a href="https://feest-282ef.firebaseapp.com"><img class="grayscale" src="../assets/FeestLand.jpg"></a>
      <a href="https://thymeshare-1501866686740.firebaseapp.com/"><img class="grayscale" src="../assets/ThymeShareLand.jpg"></a>
      <a href="http://city-block.herokuapp.com/#/"><img class="grayscale" src="../assets/cityBlockWide.jpg"></a>
      <a href="http://magpiesupply.com/"><img class="grayscale" src="../assets/MagpieImage.png"></a>

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
  height: 148vh;
}

img {
  width: 90%;
  margin-left: 5%;
  height: 25%;
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
    margin-left: 5%;
    margin-bottom: 5%;
  }

</style>

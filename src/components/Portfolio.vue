<template>
  <div id="portfolio" class="portfolio">
    <h3>Portfolio:</h3>
      <a href="https://www.havenly.com"><img class="grayscale" src="../assets/havenly.svg"></a>
      <a href="https://prspctv-1508732770742.firebaseapp.com/">
        <div class="prspctvContainer">
          <img class="grayscale prspctv" src="../assets/LogoBlueWhite.png">
        </div>
      </a>
      <a href="https://feest-282ef.firebaseapp.com"><img class="grayscale" src="../assets/FeestLand.jpg"></a>
      <a href="https://thymeshare-1501866686740.firebaseapp.com/"><img class="grayscale" src="../assets/ThymeShareLand.jpg"></a>
      <a href="http://city-block.herokuapp.com/#/"><img class="grayscale" src="../assets/cityBlockWide.jpg"></a>
      <a href="http://magpiesupply.com/"><img class="grayscale" src="../assets/MagpieImage.png"></a>

    </div>
</template>

<script>

import havenly from '../assets/havenly.svg'
import LogoBlueWhite from '../assets/LogoBlueWhite.png'
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
  height: 20%;
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

  .prspctvContainer {
    width: 90%;
    margin-left: 5%;
    height: 20%;
    background-color: black;
    display: block;
    margin-bottom: 10px;
  }

  .prspctv {
    vertical-align: middle;
    width: 50%;
    height: 200px;
    margin-top: 2%;
    margin-left: 25%;

    /*width: 300px;*/
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

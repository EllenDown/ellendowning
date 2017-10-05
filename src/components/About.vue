<template>
  <div id="about" class="about">
    <h3>Who Am I:</h3>
    <img class="grayscale" src="../assets/PortfolioMap.png">
  </div>
</template>

<script>

import PortfolioMap from '../assets/PortfolioMap.png'

export default {
  name: 'about'
}
</script>

<style scoped>

img.grayscale {
  filter: gray;
  -webkit-filter: grayscale(100%);
  -webkit-transition: all .6s ease;
  -webkit-backface-visibility: hidden;
  margin-left: 5%;
  margin-top: 5%;
  margin-bottom: 5%;
  width: 90%;
  height: 100vh;
}

img.grayscale:hover {
  filter: none;
  -webkit-filter: grayscale(0%);
}

h3 {
  width: 70%;
  font-size: 2rem;
  font-family: 'Unica One', cursive;
  border-left: thick solid black;
  padding-left: 20px;
  margin-left: 5%;
}

</style>

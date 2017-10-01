<template>
  <div class="contact">
    <div class="contactText">
      <h3>Contact:</h3>
    </div>
      <a href="https://www.linkedin.com/in/ellen-downing/"><img class="grayscale" src="../assets/LinkedIn.jpg"></a>
      <a href="https://github.com/EllenDown"><img class="grayscale" src="../assets/GitHub.jpg"></a>
      <a href="https://www.dropbox.com/s/unmvul5028fepin/EllenDowning-Resume.pdf?dl=0"><img class="grayscale" src="../assets/Resume.jpg"></a>

  </div>

</template>

<script>

import AboutImage from '../assets/AboutImage.jpg'
import LinkedIn from '../assets/LinkedIn.jpg'
import GitHub from '../assets/GitHub.jpg'
import Resume from '../assets/Resume.jpg'

export default {
  name: 'contact'
}
</script>

<style scoped>

h3 {
  font-size: 2rem;
  font-family: 'Unica One', cursive;
  border-left: thick solid black;
  padding-left: 20px;
}

img {
  width: 32.8%;
  height: 200px;
  position: relative;
}

i {
  position: absolute;
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

</style>

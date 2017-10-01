<template>
  <div class="about">
    <h3>Who Am I:</h3>
    <p class="aboutText">Retired from a life in medical research at a young age to explore a career in the energizing, challenging, and inspiring field of web development. I am a go-getter, home baked right in Denver. Speaking of baking, I love to explore and animate with my community with edible experiences just like I find my own innate vitality semi-lost on a mountain trail. Based on the partially-educated but largely intuitive feeling that is brewing within, I believe that by pursuing an entrepreneurial life in technology and development I will achieve the constant chew of creativity my mind begs for and embolden the connection I have with this community and city I belong to.</p>
  </div>
</template>

<script>

import AboutImage from '../assets/AboutImage.jpg'

export default {
  name: 'about'
}
</script>

<style scoped>

.aboutText {
  width: 80%;
  line-height: 1.6rem;
  letter-spacing: .1rem;
  margin: auto;
  margin-bottom: 30px;
}

h3 {
  width: 70%;
  font-size: 2rem;
  font-family: 'Unica One', cursive;
  border-left: thick solid black;
  padding-left: 20px;
  outline-color: invert;
}

</style>

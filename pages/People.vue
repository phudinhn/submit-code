<template>
  <div class="container">
    <div class="left">
        <nuxt-link class="navigation" to="about">Previous Article<i class='arrow up'></i></nuxt-link>
      <div class="head-space">
        <div class="dot-polka"></div>
        <nuxt-link class="head-navigation" to="people-first">Ground Control To Major Tom</nuxt-link>
      </div>
      <p>Discover those who paved the wave for human exploration of space. Across the planet from the steppe of Baikonur
         to the sunny and humid Florida, these men and women paved the ways for humanity's first steps toward becoming
         a space-faring specie, many of whom making the ultimate sacrifice in the process.
      </p>
      <nuxt-link class="body-navigation" to="people-first">Enter</nuxt-link>
      <nuxt-link class="navigation" to="timeline">Next Article<i class='arrow down'></i></nuxt-link>
    </div>
    <div class="right">

    </div>
  </div>
</template>

<style scoped>
.right {
    background-image: url("../assets/gagarin.jpg");
}

.head-space {
    margin-bottom: 3em;
}

.head-navigation {
  font-size: 3.9em;
  letter-spacing: -4px;
}

.head-navigation:hover {
  padding-left: 10px;
  color: #f47605;
}

.navigation:hover {
  color: #f47605;
}

.dot-polka {
  background: linear-gradient(90deg, #f5f5f5, 20px, rgba(248, 237, 237, 0) 1%) center, linear-gradient(#f5f5f5 20px, rgba(254, 254, 254, 0) 1%) center, #f47605;
  background-size: auto auto, auto auto, auto auto;
  background-size: 22px 22px;
  width: 15%;
  height: 33vh;
  position: absolute;
  -webkit-clip-path: polygon(0% 15%, 0 0, 15% 0%, 58% 0, 58% 38%, 100% 38%, 100% 85%, 100% 100%, 85% 100%, 15% 100%, 0 100%, 0% 85%);
  clip-path: polygon(0% 15%, 0 0, 15% 0%, 58% 0, 58% 38%, 100% 38%, 100% 85%, 100% 100%, 85% 100%, 15% 100%, 0 100%, 0% 85%);
}

.body-navigation:hover {
  transform: scale(1.3);
  color: #f47605;
}
</style>

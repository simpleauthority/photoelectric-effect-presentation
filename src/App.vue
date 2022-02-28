<script setup>
import PresentationContainer from './components/presentation/PresentationContainer.vue';
import AAATitleSlide from "./components/presentation/slides/AAATitleSlide.vue"
import BBBSecondSlide from "./components/presentation/slides/BBBSecondSlide.vue"
</script>

<template>
  <PresentationContainer id="#app">
    <AAATitleSlide />
    <BBBSecondSlide />
    <section>
  <h2>The Lorenz Equations</h2>
  \[\begin{aligned}
  \dot{x} &amp; = \sigma(y-x) \\
  \dot{y} &amp; = \rho x - y - xz \\
  \dot{z} &amp; = -\beta z + xy
  \end{aligned} \]
</section>
<section>
  
</section>
  </PresentationContainer>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  height: 90vh;
}
</style>


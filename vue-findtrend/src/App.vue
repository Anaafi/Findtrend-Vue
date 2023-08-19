<script setup>
import TheSectionFour from './components/TheSectionFour.vue';
import TheSectionThree from './components/TheSectionThree.vue';
import TheSectionTwo from './components/TheSectionTwo.vue';
import TheNavbar from './components/TheNavbar.vue';
import TheHero from './components/TheHero.vue';
</script>

<template>
<div>
  <section class="main">
    <nav>
      <TheNavbar />
    </nav>
    <TheHero />
  </section>
  <TheSectionTwo />
  <TheSectionThree />
  <the-section-four />
</div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600;700;800;900&display=swap');
.main{
  background-color: black;
}

@media (min-width: 1024px){
  nav{
    padding: 0px 30px;
  }
}

@media (min-width: 1135px){
  nav{
    padding: 0px 80px;
  }
}

</style>

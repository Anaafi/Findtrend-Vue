<script setup>
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
</div>
</template>

<style scoped>

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

<template>
  <div>
    <Navbar />
    <Hero />
    <FeaturedProjects />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import FeaturedProjects from './components/FeaturedProjects.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Hero,
    FeaturedProjects
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');

html,
body {
  font-family: 'Roboto Condensed', sans-serif;
}

#app {
  font-family: 'Roboto Condensed', sans-serif;
}
</style>

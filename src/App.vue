<template>
  <div>
    <TheHeader />
    <SideMenu />
    <About />
    <Projects />
    <Technologies />
    <Contact />
  </div>
</template>

<script setup>
import TheHeader from './components/TheHeader.vue';
import SideMenu from './components/SideMenu.vue';
import Main from './components/About.vue';
import About from './components/About.vue';
import Projects from './components/Projects.vue';
import Technologies from './components/Technologies.vue';
import Contact from './components/Contact.vue';
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 20px 20px;
  scroll-behavior: smooth;
}
</style>

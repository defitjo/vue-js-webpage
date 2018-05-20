<template>
  <div id="app">
    <app-nav></app-nav>
    <app-section v-bind:title="title"></app-section>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Nav from './components/Nav.vue';
import Section from './components/Section.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'app',
  components: {
    'app-nav': Nav,
    'app-section': Section,
    'app-footer': Footer,
  },
  data() {
    return {
      title: 'Welcome to Lorem Ipsum',
    }
  }
}
</script>

<style>
  body {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    margin: 0;
  }
</style>

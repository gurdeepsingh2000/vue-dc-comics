<template>
  <div id="app">
    <Header />
    <Main />
    <SectionBlu />
    <Footer />
  </div>
</template>




<script>

import Header from './components/Header.vue';
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import SectionBlu from './components/SectionBlu.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    SectionBlu,
    Footer
  }
}
</script>

<style lang="scss">
@import "./style/app.scss"
</style>

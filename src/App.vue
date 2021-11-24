<template>
  <div id="app">
    <Header></Header>
    <MainContent></MainContent>
    <Footer></Footer>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import MainContent from './components/MainContent.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    MainContent,
    Footer
  }
}

</script>

<style lang="scss">


</style>

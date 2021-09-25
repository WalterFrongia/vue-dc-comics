<template>
  <div id="app">
    <Header/>
    <Main/>
    <Infosection/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Infosection from './components/Infosection.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Infosection,
    Footer
  }
}
</script>

<style lang="scss">

@import "./style/variables.scss";

#app {
}
</style>

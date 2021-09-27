<template>
  <div id="app">
    <Header/>
    <Content/>
    <Infosection/>
    <Footer/>
    <MiniFooter/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Infosection from './components/Infosection.vue'
import Footer from './components/Footer.vue'
import MiniFooter from './components/MiniFooter.vue'


export default {
  name: 'App',
  components: {
    Header,
    Content,
    Infosection,
    Footer,
    MiniFooter
  }
}
</script>

<style lang="scss">

@import "./style/variables.scss";
@import "./style/general.scss";


#app {
}
</style>

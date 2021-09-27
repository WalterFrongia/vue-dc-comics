<template>
  <div id="app">
    <Header/>
    <Main/>
    <Infosection/>
    <Footer/>
    <MiniFooter/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Infosection from './components/Infosection.vue'
import Footer from './components/Footer.vue'
import MiniFooter from './components/MiniFooter.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Infosection,
    Footer,
    MiniFooter
  }
}
</script>

<style lang="scss">

@import "./style/variables.scss";
@import "./style/general.scss";

// *{
//   margin:0;
//   padding:0;
//   box-sizing: border-box;
// }
#app {
}
</style>

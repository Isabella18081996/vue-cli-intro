<template>
  <div id="app">

    <HeaderComp />

    <Main />

    <FooterComp />

  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import Main from '@/components/Main.vue'  /* @ parto da src e vado a prendere main  */
import FooterComp from './components/FooterComp.vue'


export default {
  name: 'App',
  components: {
    HeaderComp,
    Main,
    FooterComp
    
  }
}
</script>

<style>

</style>

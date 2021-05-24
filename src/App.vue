<template>

  <div id="app">

    <HeaderComp />

    <Jumbotron />

    <MainComp />

    <SectionComp />

    <FooterCompTop />

    <FooterCompBottom />

  </div>

</template>

<script>
  import HeaderComp from '@/components/HeaderComp'
  import MainComp from '@/components/MainComp'
  import SectionComp from '@/components/SectionComp.vue'
  import FooterCompTop from '@/components/FooterCompTop.vue'
  import FooterCompBottom from '@/components/FooterCompBottom.vue'
  import Jumbotron from '@/components/Jumbotron.vue'
export default {

  name: 'App',
  components: {
    HeaderComp,
    Jumbotron,
    MainComp,
    SectionComp,
    FooterCompTop,
    FooterCompBottom
  }
}
</script>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>

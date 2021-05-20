<template>

  <div id="app">

    <HeaderComp />

    <MainComp />

    <SectionComp />

  </div>

</template>

<script>
  import HeaderComp from '@/components/HeaderComp'
  import MainComp from '@/components/MainComp'
  import SectionComp from '@/components/SectionComp.vue'
export default {

  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    SectionComp
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

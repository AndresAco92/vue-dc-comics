<template>
  <main>
    <div class="box">
     <p> Content goes here </p> 
    </div>
  </main>
</template>

<script>
export default {
  name:'MainComp'
}
</script>

<style lang='scss' scoped>
  main{
    width: 100%;
    height: 130px;
    background: #000;
    .box{
      width: 66%;
      height: 100%;
      margin: 0 auto;
      display: flex;
      align-items: center;
      p{
      color: #fff;
      font-size: 30px;
      display: flex;
        &::after{
          content: '<--';
          display: table;
          clear: both;
        }
        &::before{
          content: '-->';
          display: table;
          clear: both;
        }
      }
    }
  }
</style>
<template>
  <main>
    <div class="box">
      <div class="btn_top">CURRENT SERIES</div>
      <Comics
            v-for="(cover, index) in Riviste" :key='index'
            :card="cover"
      />
      <div class="btn_bottom">LOAD MORE</div>
    </div>
    

  </main>
</template>

<script>

  import Riviste from "@/assets/data/dc-comics.js"
  import Comics from "@/components/CardMain.vue"

export default {
  name:'MainComp',
  components:{
    Comics
  },
  data(){
    return{
      Riviste
    }
  }
}
</script>

<style lang='scss' scoped>
  main{
    width: 100%;
    height: 670px;
    background: #1C1C1C;
    .box{
      width: 67%;
      height: 100%;
      margin: 0 auto;
      padding-top: 50px;
      display: flex;
      flex-wrap: wrap;
      position: relative;
      .btn_top,
      .btn_bottom{
        background-color: #0282F9;
        color: #fff;
        cursor: pointer;
        position: absolute;
      }
      .btn_top{  
        top: -25px;
        left: -15px;
        font-size: 25px;
        padding: 10px 27px;
      }
      .btn_bottom{
        bottom: 15px;
        left: 50%;
        transform: translate(-50%);
        font-size: 13px;
        padding: 10px 60px;
      }
      .btn_top:hover{
        transform: scale(1.1);
      }
    }
  }
</style>
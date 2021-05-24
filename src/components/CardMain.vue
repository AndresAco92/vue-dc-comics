<template>
  
  <div class="card">
    <div class="img_cover">
      <img :src="card.thumb" :alt="card.type">
    </div>
    <h2>{{card.series.toUpperCase()}}</h2>
  </div>

</template>

<script>
export default {
  name: 'CardMain',
  props:{
    card: Object
  }
}
</script>

<style lang='scss' scoped>
  .card{
    flex-basis: calc(100% / 6);
    color: #fff;
    overflow: hidden;
    &:hover{
      transform: scale(1.1);
      cursor: pointer;
    }
    .img_cover{
      width: 186px;
      height: 187px;
      overflow: hidden;
      img{
       width: 100%;
      }
    }
    h2{
      font-size: 15px;
      margin-top: 15px
    }
  }
</style>
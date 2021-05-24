<template>
  
  <header class="container">
    <div class="box">
      <a href="/">
        <img src="../assets/img/dc-logo.png" alt="logo-dc">
      </a>
      <ul>
        <li v-for="(link, index) in links" 
            :key= "index"
        >
          <a :href="link.url"
             :class="{'active': link.current}"
          >
            {{link.text}}
          </a>
        </li> 
      </ul>
    </div>
  </header>

</template>

<script>
export default {
  name: 'HeaderComp',
  data(){
    return{
      links:[
        {
          text:'CHARACTERS',
          url:'#',
          current: false
        },
        {
          text:'COMICS',
          url:'#',
          current: true
        },
        {
          text:'MOVIES',
          url:'#',
          current: false
        },
        {
          text:'TV',
          url:'#',
          current: false
        },
        {
          text:'GAMES',
          url:'#',
          current: false
        },
        {
          text:'COLLECTIBLES',
          url:'#',
          current: false
        },
        {
          text:'VIDEOS',
          url:'#',
          current: false
        },
        {
          text:'FANS',
          url:'#',
          current: false
        },
        {
          text:'NEWS',
          url:'#',
          current: false
        },
        {
          text:'SHOP',
          url:'#',
          current: false
        }
      ]
    }
  }
}
</script>

<style lang='scss' scoped>

  header{
    width: 100%;
    height: 120px;
    .box{
      width: 67%;
      height: 100%;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      img{
        width: 80px;
        &:hover{
          transform: scale(1.1);
        }        
      }
      ul{
        width: 60%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        list-style: none;
        a{
          text-decoration: none;
          padding-bottom: 45px;
          color: #000;
          &:hover{
            color: #0282F9;
          }
          &.active{
            border-bottom:6px solid  #0282F9;
            color: #0282F9;
          }
        }
      }
    }
  }
</style>
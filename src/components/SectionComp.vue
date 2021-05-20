<template>
  <section>
    <div class="box">
      <ul>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="card">
          <span>DIGITAL COMICS</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="card">
          <span>DIGITAL COMICS</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="card">
          <span>DIGITAL COMICS</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="card">
          <span>DIGITAL COMICS</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="card">
          <span>DIGITAL COMICS</span>
        </li>
      </ul>   
    </div>
  </section>
</template>

<script>
export default {
  nome:'SectionComp'
}
</script>

<style lang='scss' scoped>
  section{
    width: 100%;
    height: 160px;
    background-color: #0282F9;
    .box{
      width: 67%;
      height: 100%;
      margin: 0 auto;
      display: flex;
      align-items: center;
      color: #fff;
      ul{
        width: 100%;
        display: flex;
        justify-content: space-around;
        list-style: none;
        li{
          display: flex;
          align-items: center;
          img{
          width: 60px;
          margin-right: 10px;
        }
        }
      }
    }
  }
</style>
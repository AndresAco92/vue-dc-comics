<template>
  <section>
    <div class="box">
      <ul>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="smart">
          <span>DIGITAL COMICS</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-merchandise.png" alt="t-shirt">
          <span>DC MERCHANDISE</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="cards">
          <span>SUBSCRIPTION</span>
        </li>
        <li>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="position">
          <span>COMIC SHOP LOCATOR</span>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="cash">
          <span>DC POWER VISA</span>
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
      color: #fff;
      ul{
        height: 100%;
        width: 100%;
        display: flex;
        justify-content: space-around;
        align-items: center;
        list-style: none;
        li{
          cursor: pointer;
          &:hover{
            transform: scale(1.1);
          }
          img{
            height: 55px;
            max-width: 60px;
            padding-right: 10px;
            vertical-align: middle;
          }
        }
      }
    }
  }
</style>
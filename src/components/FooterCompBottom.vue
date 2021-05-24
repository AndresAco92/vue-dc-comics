<template>

  <footer>
    <div class="box">
      <div class="left">
        <button class="disabled">SIGN-UP NOW!</button>
      </div>
      <div class="right">
        <ul>
          <li><a href="#">FOLLOW US</a></li>
          <li><img src="../assets/img/footer-facebook.png" alt="facebook"></li>
          <li><img src="../assets/img/footer-twitter.png" alt="twitter"></li>
          <li><img src="../assets/img/footer-youtube.png" alt="youtube"></li>
          <li><img src="../assets/img/footer-pinterest.png" alt="pinterest"></li>
          <li><img src="../assets/img/footer-periscope.png" alt="periscope"></li>          
        </ul>
      </div>
    </div>
  </footer>

</template>

<script>
export default {
  name: 'FooterCompBottom'
}
</script>

<style lang='scss' scoped>
  footer{
    width: 100%;
    height: 110px;
    background-color: #303030;
    .box{
      width: 67%;
      height: 100%;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      button{
        background-color: #303030;
        border: 2px solid #0E81F9;
        color: #fff;
        padding: 15px;
        font-size: 1em;
        cursor: pointer;
        &:hover{
          transform: scale(1.1);
        }
      }
      ul{
        display: flex;
        list-style: none;
        li{
          margin-left: 18px;
          display: flex;
          align-items: center;
          &:hover{
          transform: scale(1.1);
          cursor: pointer;
          }
          a{
          text-decoration: none;
          color: #0E81F9;
          font-size: 20px;
          }
        }
      }
    }
  }
</style>
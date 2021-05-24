<template>

  <footer>
    <div class="box">
      <div class="footer_left">
        <div>
          <h2>DC COMICS</h2>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h2>SHOP</h2>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>  
        </div>
        <div>
          <h2>DC</h2>
          <ul>
            <li><a href="#">Terms of Use</a></li>
            <li><a href="#">Privacy policy(New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div>
          <h2>SITES</h2>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <div class="footer_right"></div>
    </div>
  </footer>
  
</template>

<script>
export default {

}
</script>

<style lang='scss' scoped>

  footer{
    width: 100%;
    height: 370px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    .box{
      width: 67%;
      height: 100%;
      margin: 0 auto;
      .footer_left,
      .footer_right{
        float: left;
        width: 50%;
        height: 100%;
        color: #fff;
      }
      .footer_left{
        padding: 40px 0;
        display: flex;
        flex-basis: calc(100% / 3);
        div{
          font-size: 14px;
          margin-right: 30px;
          line-height: 20px;
          h2{
            margin: 15px 0;
          }
          ul{
            list-style: none;
            a{
            text-decoration: none;
            color: #fff;
            opacity: 0.5;
            &:hover{
              cursor: pointer;
              opacity: 1;
            }
            }
          }
        }
      }
      .footer_right{
        background-image: url(../assets/img/dc-logo-bg.png);
        background-size: 560px;
        background-repeat: no-repeat;
        background-position: 10px;
        background-position-x: 75px;
        overflow: hidden;
      }
    }
  }

</style>
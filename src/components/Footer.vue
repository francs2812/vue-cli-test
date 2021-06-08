<template>
  <footer>
      <span>
          <ul>
              <li class="title"> <a href="#"><strong>DC COMICS</strong></a> </li>
              <li> <a href="#">Characters</a> </li>
              <li> <a href="#">Comics</a> </li>
              <li> <a href="#">Movies</a> </li>
              <li> <a href="#">TV</a> </li>
              <li> <a href="#">Games</a> </li>
              <li> <a href="#">Videos</a> </li>
              <li> <a href="#">News</a> </li>
              <li class="title"> <a href="#"><strong>SHOP</strong></a> </li>
              <li> <a href="#">Shop DC</a> </li>
              <li> <a href="#">Shop DC Collectibles</a> </li>
          </ul>
          <ul>
              <li class="title"> <a href="#"><strong>DC</strong></a> </li>
              <li> <a href="#">Terms Of Use</a> </li>
              <li> <a href="#">Privacy policy(New)</a> </li>
              <li> <a href="#">Ad Choices</a> </li>
              <li> <a href="#">Advertising</a> </li>
              <li> <a href="#">Jobs</a> </li>
              <li> <a href="#">Subscriptions</a> </li>
              <li> <a href="#">Talent Workshops</a> </li>
              <li> <a href="#">CPSC Certificates</a> </li>
              <li> <a href="#">Ratings</a> </li>
              <li> <a href="#">Shop Help</a> </li>
              <li> <a href="#">Contact Us</a> </li>
          </ul>
          <ul>
              <li class="title"> <a href="#"><strong>SITES</strong></a> </li>
              <li> <a href="#">DC</a> </li>
              <li> <a href="#">MAD Magazine</a> </li>
              <li> <a href="#">DC Kids</a> </li>
              <li> <a href="#">DC Universe</a> </li>
              <li> <a href="#">DC Power Visa</a> </li>
          </ul>
          <img id="logo-bd" src="../assets/img/dc-logo-bg.png" alt="">
      </span>
      <div>
        <h1>sing-up now!</h1>
        <div>
            <h3>follow us</h3>
            <img src="../assets/img/footer-facebook.png" alt="">
            <img src="../assets/img/footer-twitter.png" alt="">
            <img src="../assets/img/footer-youtube.png" alt="">
            <img src="../assets/img/footer-pinterest.png" alt="">
            <img src="../assets/img/footer-periscope.png" alt="">
            
        </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: "Footer"

}
</script>

<style lang="scss" scoped>
    @import "./style/general";
    footer {
        display: flex;
        flex-direction: column;
        width: 100%;
        background-image: url("../assets/img/footer-bg.jpg");
    }
    a {
        text-decoration: none;
        color:gray;
    }
    span {
        overflow: hidden;
        position: relative;
        ul {
            float: left;
            margin:10px 20px;

            li {
                list-style: none;
            }
        }
        #logo-bd {
            height: 400px;
            transform: translate(-50%, -50%);
            position: absolute;
            top: 50%;
            right: 0;
            padding: 25px;
        }
    }
    footer > div:last-child {
            height: 70px;
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color: #202020;

            h1 {
                display: inline-block;
                @include botton;
            }
            img {
                height: 25px;
                margin: 0 10px;
            }

            h3 {
                text-transform: uppercase;
                color: $colorBrand;
                float: left;
            }
    }

    .title {
        margin:15px 0;
        a {
            color: white;
        }
    }
    

</style>
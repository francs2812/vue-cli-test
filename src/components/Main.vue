<template>
  <main>
      <div id="shop">
          <div id="titans"></div>
          <div id="element">
              <h1>current series</h1>
              <div id="comics">
                  <Comics />
              </div>
          </div>
          
      </div>
      <nav>
          <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>digital comincs</p>
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>dc merchandise</p>
            </li>

            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>subscription</p>
            </li>

            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>dc pawer visa</p>
            </li>

            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>comic shop locator</p>
            </li>

          </ul>
      </nav>
  </main>
</template>

<script>
import Comics from './Comics.vue'


export default {
    name: 'Main',
    components: {
        Comics
    }
}
</script>

<style lang="scss" scoped>
    //$colorBrand : #0282f9;
    @import "./style/general";
    main {
        display: block;
        //height: 70vh;
        color: white;
        margin-top: 0;

        #shop {
            height: 85%;

            #titans {
                height: 50vh;
                background-image: url(../assets/img/jumbotron.jpg);
                background-size: cover;
            }
            #element {
                position: relative;
                //background-color: black;
                h1 {
                    transform: translate(-50%, -50%);
                    position: absolute;
                    top: 0;
                    left: 15%;
                    font-size: 19px;
                    padding: 10px;
                    display: inline-block;
                    text-transform: uppercase;
                    color: white;
                    background-color: $colorBrand;
                }
                #comics {
                    height: 100%;
                    
                }
            }
        }
        nav {
            height: 80px;
            background-color: $colorBrand;
            display: flex;
            justify-content: center;
            align-items: center;


            ul {
                height: 70%;
                width: 70%;
                display: flex;
                justify-content: center;
                align-items: center;

                li {
                    height: 100%;
                    font-size: 10px;
                    padding: 10px;
                    list-style: none;
                    display: flex;
                    align-items: center;
                    cursor: pointer;
                    

                    img {
                        height: 100%;
                    }

                    p {
                        text-transform: uppercase;
                        margin: 0 15px;
                        display: block;
                    }
                }
            }
        }


    }
</style>
<template>
  <main>
      <div>contenuto</div>
      <div>
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
      </div>
  </main>
</template>

<script>
export default {
    name: "Main"
}
</script>

<style lang="scss" scoped>
    main {
        height: 70vh;
        color: white;
        margin-top: 0;

        div {
            height: 85%;
            background-color: black;
        }
        div:last-child {
            height: 15%;
            background-color: blue;
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
                    height: 50%;
                    font-size: 10px;
                    padding: 10px;
                    list-style: none;
                    display: flex;
                    align-items: center;
                    

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
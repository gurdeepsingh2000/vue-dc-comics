<template>
    <div>
        <div class="container-fluid black-row">
            <div class="container blocks">
                <span id="text">Content Goes Here</span>
            </div>
        </div>
        <div class="container-fluid sky-row">
            <div class="container items">

                <div class="benefits">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                    <p>DIGITAL COMICS</p>
                </div>

                <div class="benefits">
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                    <p>DC MERCHANDISE</p>
                </div>

                <div class="benefits">
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                    <p>SUBSCRIPTION</p>
                </div>

                <div class="benefits">
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                    <p>COMIC SHOP LOCATOR</p>
                </div>

                <div class="benefits">
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                    <p>DC POWER VISA</p>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
export default {
    name: 'Main'
}
</script>


<style lang="scss" scoped>
    .black-row{
        background: black;

        .blocks{
            padding: 100px 0px
            }

            #text{
            color: white;
        }
    }

    .sky-row{
        background: #0282F9;

        .items{
            height: 200px;
            display: flex;


            .benefits{
                display: flex;
                align-items: center;
                width: 100%;
                justify-content: space-evenly;
                margin-left: 20px;

                p{
                    font-size: 14px;
                    color: white;
                }

                img{
                    width: 26%;
                }
            }
        }
    }
</style>

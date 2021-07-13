<template>
    <div>
        <div class="container-fluid bg-img">
            <div class="container list-menu">

                <ul>
                    <li><h3>DC COMICS</h3></li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>

                    <li><h3>SHOP</h3></li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>

                <ul>
                    <li><h3>DC</h3></li>
                    <li>Terms Of Use</li>
                    <li>Privacy policy(New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>

                <ul>
                    <li><h3>SITES</h3></li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>

            </div>
        </div>
        <div class="container-fluid footer-buttons">
            <div class="container list-menu"></div>
        </div>
    </div>

</template>

<script>
export default {
    name: 'Footer'
}
</script>


<style lang="scss" scoped>
    .bg-img{
        background-image: url('../assets/footer-bg.jpg');
        background-size: cover;
        height: 400px;
        position: relative;

        .list-menu{
            display: flex;
            justify-content: flex-start;

            ul{
                margin-top: 30px;
                margin-right: 60px;
            }

            li{
            margin-top: 4px;
            list-style: none;
            color: gray;


            h3{
                color: white;
                padding-top: 30px;
            }
        }
            
        }
    }

    .footer-buttons{
        background-color: #303030;
        height: 102px;
    }

</style>

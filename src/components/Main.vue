<template>
    <div>
        <div class="container-fluid black-row">
            <div class="container blocks">
                <span id="text">Content Goes Here</span>
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

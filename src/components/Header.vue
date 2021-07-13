<template>
    <div class="navbar container">
        <div class="logo-container">
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <div class="menu-list">
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>


<style lang="scss" scoped>
    .navbar{
        margin-top: 6px;
        display: flex;
        justify-content: center;
        align-items: center;
        justify-content: space-between;
        margin-bottom:7px;

        .menu-list ul{
            display: flex;

            li{
                margin: 9px;
                list-style: none;
                

                &:hover{
                    text-decoration-line: underline;
                    text-underline-offset: 45px;
                    text-decoration-thickness: 7px;
                    color: #0282F9;
                }
            }
            
        }
    }
</style>

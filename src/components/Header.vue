<template>
    <div class="container-elements-margin">
        <header>
            <a href="#" class="logo-brand">
                <img src="../assets/images/dc-logo.png" alt="">
            </a>
            <nav class="header-navigation">
                <ul class="navigation-list">
                    <li>
                        <a href="#">CHARACTERS</a>
                    </li>
                    <li>
                        <a href="#">COMICS</a>
                    </li>
                    <li>
                        <a href="#">MOVIES</a>
                    </li>
                    <li>
                        <a href="#">TV</a>
                    </li>
                    <li>
                        <a href="#">GAMES</a>
                    </li>
                    <li>
                        <a href="#">COLLECTIBLES</a>
                    </li>
                    <li>
                        <a href="#">VIDEOS</a>
                    </li>
                    <li>
                        <a href="#">FANS</a>
                    </li>
                    <li>
                        <a href="#">NEWS</a>
                    </li>
                    <li>
                        <a href="#">SHOP</a>
                    </li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}

.container-elements-margin{
    margin:auto;
    width:90%;
}

header{
    display:flex;
    align-items: center;
    justify-content: space-between;
    padding-top:10px;
}

ul{
    display:flex;
    flex-direction: row;
}

li{
    padding:40px 10px 70px 10px;
    list-style-type: none;
    border-bottom:3px solid transparent;
    &:hover{
        border-bottom:3px solid blue;
    }
}

a{
    text-decoration: none;
    color:black;
}
</style>
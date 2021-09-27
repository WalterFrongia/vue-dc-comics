<template>
    <div id="container-elements-margin">
        <header>
            <a href="#" class="logo-brand">
                <img src="../assets/images/dc-logo.png" alt="">
            </a>
            <nav class="header-navigation">
                <ul class="navigation-list">
                    <li v-for="link in navBarLinks" :key="link.name">{{link.name}}</li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<script>
export default {
    data(){
        return{
            //LINKS NAVBAR
            navBarLinks:[
                {
                    name:"CHARACTERS"
                },
                {
                    name:"COMICS"
                },
                {
                    name:"MOVIES"
                },
                {
                    name:"TV"
                },
                {
                    name:"GAMES"
                },
                {
                    name:"COLLECTIBLES"
                },
                {
                    name:"VIDEOS"
                },
                {
                    name:"FANS"
                },
                {
                    name:"NEWS"
                },
                {
                    name:"SHOP"
                },
            ],
        }
    }

}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";
@import "../style/general.scss";

//MARGIN
#container-elements-margin{
    margin:auto;
    width:90%;
}
//FINE MARGIN

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
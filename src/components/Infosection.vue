<template>
    <div class="info-section-container">
        <div id="container-elements-margin">
            <ul class="container-info-list">
                <li>
                    <a href="">
                        <img src="../assets/images/buy-comics-digital-comics.png" alt="">
                        <span>DIGITAL COMICS</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/images/buy-comics-merchandise.png" alt="">
                        <span>DC MERCHANDISE</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/images/buy-comics-subscriptions.png" alt="">
                        <span>SUBSCRIPTION</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/images/buy-comics-shop-locator.png" alt="">
                        <span>COMIC SHOP LOCATOR</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/images/buy-dc-power-visa.svg" alt="">
                        <span>DC POWER VISA</span>
                    </a>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {

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

ul{
    list-style-type: none;
    display: flex;
    align-items: center;
}

a{
    text-decoration: none;
    display: flex;
    align-items: center;
    img{
        height: 50px;
        padding-right: 10px;
    }
    span{
        color:white;
    }
}

.container-info-list{
    display: flex;
    justify-content: space-evenly;
}

.info-section-container{
    background-color:$primaryColor;
    display:flex;
    justify-content: space-between;
    padding:60px 0;

}

</style>
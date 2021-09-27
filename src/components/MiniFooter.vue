<template>

    <div id="mini-footer-section">
        <div id="container-elements-margin" class="flex-container">
            <div id="button-section">
                <button>SIGN-UP NOW!</button>
            </div>

            <div id="social-section">
                <h3>FOLLOW US</h3>
                <img src="../assets/images/footer-facebook.png" alt="">
                <img src="../assets/images/footer-twitter.png" alt="">
                <img src="../assets/images/footer-youtube.png" alt="">
                <img src="../assets/images/footer-pinterest.png" alt="">
                <img src="../assets/images/footer-periscope.png" alt="">
            </div>
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

#mini-footer-section{
    background-color: rgb(61, 60, 60);

    padding:40px 0;
}

button{
    padding:20px 30px;
    background-color: transparent;
    border:3px solid $primaryColor;
    color:white;
}

.flex-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

#social-section{
    display: flex;
    align-items: center;
    h3{
        padding-right: 10px;
        color:$primaryColor;
    }
    img{
        padding:0 5px;
    }
}
</style>
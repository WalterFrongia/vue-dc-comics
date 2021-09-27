<template>
    <div>
        <div id="jumbotron-section">
            <div id="container-elements-margin">
            <button>CURRENT SERIES</button>
            </div>
        </div>
        <div id="container-content">

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

h1{
    color:white;
}

#jumbotron-section{
    padding:60px 0;
    background-image: url(../assets/images/jumbotron.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 350px;

    position:relative;
    button{

        background-color: $primaryColor;
        color:white;
        padding:10px 20px;
        border:none;
        
        position:absolute;
        bottom:-20px;
    }
}

#container-content{
    height: 300px; //altezza per visualizzare gli spazi, poi va rimossa
    background-color: rgb(36, 36, 36);
}

</style>
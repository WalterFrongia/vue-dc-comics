<template>
    <div id="content-section">
       <div id="container-elements-margin">
           <h1></h1>
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


#content-section{
    padding:60px 0;
    background-image: url(../assets/images/jumbotron.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}

</style>
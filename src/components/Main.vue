<template>
    <div id="content-section">
       <div id="container-elements-margin">
           <h1> Content goes here </h1>
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

//MARGINE E RESET
// *{
//     margin:0;
//     padding:0;
//     box-sizing: border-box;
// }

#container-elements-margin{
    margin:auto;
    width:90%;
}
//FINE MARGINE E RESET


h1{
    color:white;
}


#content-section{
    padding:60px 0;
    background-color:rgb(53, 51, 51);
}

</style>
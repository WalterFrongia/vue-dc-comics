<template>
    <div id="content-section">
       <div class="container-elements-margin">
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

*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}

h1{
    color:white;
}

.container-elements-margin{
    margin:auto;
    width:90%;
}

#content-section{
    padding:60px 0;
    background-color:rgb(53, 51, 51);
}

</style>
<template>
    <div class="card-element">
        <img :src="image" alt="">
    </div>
</template>

<script>
export default {
    props: ["image"],
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";
@import "../style/general.scss";

.card-element{
    // height: 150px;
    background-color: rgb(92, 92, 202);
    margin:5px;

    flex-basis: calc( 100% / 6 - 12px);
}

img{
    height: 80%;
    width:80%;
}

</style>
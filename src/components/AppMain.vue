<script>
export default {
    name: "appMain",
    props: [
        "slides"
    ]
}
</script>

<template>
    <div class="containerSlaider"></div>
    <div class="containerBox">
        <div v-for="slide in slides" class="box">
        </div>
    </div>
</template>

<style scoped>
    .containerSlaider{
        background-color: black;
        height: 400px;
    }

    .containerBox{
        height: 670px;
        padding: 30px 310px;
        background-color: bisque;
        display: flex;
        flex-wrap: wrap;
    }

    .box{
        margin: 10px;
        width: calc(100% / 6 - 20px);
        height: 245px;
        border: 1px solid black;
    }


</style>
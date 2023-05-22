<script>
export default {
    name: "appMain",
    props: {
        slides: Array
    }
       
    
}
</script>

<template>
    <div class="containerSlaider"></div>
    <div class="containerBox">
        <div v-for="slide in slides" class="box">
            <div class="boxImg">
                <img :src=" slide.thumb" alt="">
            </div>
            <div class="boxTitle">
                <h3> {{ slide.series }}</h3>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .containerSlaider{
        background-color: black;
        height: 400px;
    }

    .containerBox{
        padding: 30px 310px;
        background-color: #1c1c1c;
        display: flex;
        flex-wrap: wrap;
    }

    .box{
        margin: 10px;
        width: calc(100% / 6 - 20px);
        max-width: 195px;
    }

    .boxImg{
        width: 100%;
        height: 200px;
    }

    img{
        width: 100%;
        height: 100%;
    }

    h3{
        padding-top: 1rem;
        color: white;
    }


</style>
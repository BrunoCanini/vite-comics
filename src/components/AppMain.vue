<script>
export default {
    name: "appMain",
    props: {
        slides: Array
    }
       
    
}
</script>

<template>
    <div class="containerSlaider">
        <button class="buttonCurrent">CURREN SERIES</button>
    </div>
    <div class="containerBox">
        <div v-for="slide in slides" class="box">
            <div class="boxImg">
                <img :src=" slide.thumb" alt="">
            </div>
            <div class="boxTitle">
                <h3> {{ slide.series }}</h3>
            </div>
        </div>
        <div class="boxButton">
            <button>LOAD MORE</button>
        </div>
    </div>

</template>

<style scoped>
    .containerSlaider{
        background-color: black;
        height: 400px;
        padding: 0 310px;
        position: relative;
    }

    .containerBox{
        padding: 30px 310px;
        background-color: #1c1c1c;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
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

    .containerSlaider{
        background-image: url(/public/jumbotron.jpg);
        background-size: cover;
    }

    .boxButton{
        margin-top: 50px;
        width: 100%;
        display: flex;
        justify-content: center;
    }

    button{
        width: 185px;
        padding: 0.5rem;
        border: none;
        background-color: #0282f9;
        color: white;
    }

    .buttonCurrent{
        position: absolute;
        bottom: -22px;
        font-size: 1.5rem;
        width: 250px;
    }


</style>
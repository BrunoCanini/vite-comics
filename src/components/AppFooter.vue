<template>
    <div class="containerFooter">
        <div>
            <button>SIGN-UP NOW!</button>
        </div>
        
        <div class="right">
            <div>
                <span>FOLLOW US</span>
            </div>
            <div class="box">
                <img src="/public/footer-facebook.png" alt="">
            </div>
            <div class="box">
                <img src="/public/footer-periscope.png" alt="">
            </div>
            <div class="box">
                <img src="/public/footer-pinterest.png" alt="">
            </div>
            <div class="box">
                <img src="/public/footer-twitter.png" alt="">
            </div>
            <div class="box">
                <img src="/public/footer-youtube.png" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped>
    .containerFooter{
        height: 110px;
        background-color: #303030;
        padding: 35px 310px;
        display: flex;
        justify-content: space-between;
    }

    button{
        width: 140px;
        padding: 1rem;
        background-color: transparent;
        border: 1px solid #0282f9;
        color: white;
    }

    .right{
        display: flex;
        align-items: center;
    }

    .box{
        padding: 0.5rem;
    }

    span{
        color: #0282f9;
    }

</style>
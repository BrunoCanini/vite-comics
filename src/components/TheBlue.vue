<template>
    <div class="containerBlue">
        <div class="box">
            <div class="boxImg">
                <img src="/public/buy-comics-digital-comics.png" alt="">
            </div>
            <a href="">DIGITAL COMICS</a>
        </div>
        <div class="box">
            <div class="boxImg">
                <img src="/public/buy-comics-merchandise.png" alt="">
            </div>
            <a href="">DC MERCHANDISE</a>
        </div>
        <div class="box">
            <div class="boxImg">
                <img src="/public/buy-comics-subscriptions.png" alt="">
            </div>
            <a href="">SUBSCRIPTION</a>
        </div>
        <div class="box">
            <div class="boxImg">
                <img src="/public/buy-comics-shop-locator.png" alt="">
            </div>
            <a href="">COMIC SHOP LOCATOR</a>
        </div>
        <div class="box">
            <div class="boxImg">
                <img src="/public/buy-dc-power-visa.svg" alt="">
            </div>
            <a href="">DC POWER VISA</a>
        </div>
    </div>
</template>

<style scoped>

.containerBlue{
    width: 100%;
    background-color: #0282f9;
    padding: 50px 310px;
    display: flex;
    flex-wrap: wrap;
}

.box{
    width: calc(100% / 5);
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

.boxImg{
    height: 55px;
}

img{
    height: 100%;
}

a{
    text-decoration: none;
    color: white;
    margin-left: 0.7rem;
}

</style>
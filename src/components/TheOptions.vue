<template>
    <div class="containerOption">
        <div class="options1">

            <div class="box">
                <h2>DC COMICS</h2>
                <a href="">Characters</a>
                <br><a href="">Comics</a>
                <br><a href="">Movies</a>
                <br><a href="">TV</a>
                <br><a href="">Games</a>
                <br><a href="">Videos</a>
                <br><a href="">News</a>

                <h2>SHOP</h2>
                <a href="">Shop DC</a>
                <br><a href="">Shop DC Collectibles</a>
            </div>
            
            <div class="box">
                <h2>DC</h2>
                <a href="">Terms Of Use</a>
                <br><a href="">Privacy policy (New)</a>
                <br><a href="">Ad Choices</a>
                <br><a href="">Advertsing</a>
                <br><a href="">Jobs</a>
                <br><a href="">Subscriptions</a>
                <br><a href="">Talent Workshops</a>
                <br><a href="">CPSC Certificates</a>
                <br><a href="">Ratings</a>
                <br><a href="">Shop Help</a>
                <br><a href="">Contact Us</a>
            </div>

            <div class="box">
                <h2>SITES</h2>
                <a href="">DC</a>
                <br><a href="">MAD Magazine</a>
                <br><a href="">DC Kids</a>
                <br><a href="">DC Universe</a>
                <br><a href="">DC Power Visa</a>
            </div>
        </div>

        <div class="options2"></div>
    </div>
</template>

<style scoped>
.containerOption{
    padding: 0 310px;
    background-image: url(/public/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    flex-wrap: wrap;
    position: relative;
}

.options1{
    width: 50%;
    height: 100%;
    padding-bottom: 60px;
    padding-top: 20px;
    display: flex;
    flex-wrap: wrap;
}

.options2{
    width: 50%;
    height: 468px;
    background-image: url(/public/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: center;
    position: absolute;
    right: 0;
}

.box{
    margin-right: 55px;
}

h2{
    color: white;
    padding: 25px 0;
}

a{
    text-decoration: none;
    color: grey;
    vertical-align: 0.5rem;
}

</style>
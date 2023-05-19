<template>
    <div class="containerHeader">
        <div class="logo">
            <img src="/public/dc-logo.png" alt="">
        </div>
        <div class="nav">
            <a href="">CHARACTERS</a>
            <a href="">COMICS</a>
            <a href="">MOVIES</a>
            <a href="">TV</a>
            <a href="">GAMES</a>
            <a href="">COLLECTIBLES</a>
            <a href="">VIDEOS</a>
            <a href="">FANS</a>
            <a href="">NEWS</a>
            <a href="">SHOP</a>
        </div>
    </div>
</template>

<style scoped>
    .containerHeader{
        max-width: 1900px;
        padding: 0.5rem 250px;
        display: flex;
    }

    .logo{
        width: 90px;
        height: 90px;
    }

    img{
        width: 100%;
        height: 100%;
    }
    
    .nav{
        display: flex;
        align-items: center;
        justify-content: flex-end;
        flex-grow: 1;
    }

    a{
        margin: 0 0.8rem;
        text-decoration: none;
        color: black;
    }

    a:hover {
        color:#0282f9;
    }

</style>
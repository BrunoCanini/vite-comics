<script>
export default {
    name: "AppHeader",
    data() {
        return {
            links : [ "CHARACTERS" , "COMICS", "MOVIES", "TV", "GAMES", "COLLECTIBLES", "VIDEOS", "FANS", "NEWS", "SHOP" ]
        }
    }
}
</script>

<template>
    <div class="containerHeader">
        <div class="logo">
            <img src="/public/dc-logo.png" alt="">
        </div>
        <div class="nav">
            <a v-for="link in links" href="">{{link}}</a>
        </div>
    </div>
</template>

<style scoped>
    .containerHeader{
        padding: 0.5rem 310px;
        display: flex;
        justify-content: space-between;
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
        width: calc(100% - 90px);
        display: flex;
        align-items: center;
        justify-content: flex-end;
    }

    a{
        margin-left: 0.8rem;
        text-decoration: none;
        color: black;
    }

    a:hover {
        color:#0282f9;
    }

</style>
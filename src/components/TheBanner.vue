<template>
    <div id="main-banner">
        <h1>Faça seu lanche</h1>
    </div>
</template>

<script>
    export default{
        name: "TheBanner"
    }
</script>

<style scoped>
    #main-banner{
        background-image: url('/public/img/burger.jpg');
        background-position: 0 -250px;
        background-size: cover;
        
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        width: auto;
    }
    
    #main-banner h1{
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }
    @media (max-width: 600px) {
        #main-banner {
            height: 250px;
            background-repeat: no-repeat;
            background-position: center;
        }
        #main-banner h1{
            color: #fff;
            text-align: center;
            font-size: 18px;
            background-color: #222;
            padding: 15px;
            
            
        }
    }
</style>
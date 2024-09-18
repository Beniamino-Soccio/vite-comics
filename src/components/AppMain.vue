<script>
import MainComicsList from './MainComicsList.vue';

export default{
    data(){
        return{
            
        }
    },
    components:{
        MainComicsList,
    }
}
</script>

<template>
    <main>
        <div class="jumbotron">
            <span>CURRENT SERIES</span>
        </div>
        <div class="bg-black">
            <section class="main-content container">
                <MainComicsList/>
                <div class="button-load">
                    <a href="#">LOAD MORE</a>
                </div>
                
            </section>
        </div>

        <div class="bg-blue">
            <section class="main-links container">
                <ul>
                    <li><a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics"><p>DIGITAL COMICS</p></a></li>
                    <li><a href="#"><img src="../assets/img/buy-comics-merchandise.png" alt="dc merchandise"><p>DC MERCHANDISE</p></a></li>
                    <li><a href="#"><img src="../assets/img/buy-comics-subscriptions.png" alt="digital comics"><p>SUBSCRIPTION</p></a></li>
                    <li><a href="#"><img src="../assets/img/buy-comics-shop-locator.png" alt="shop locator"><p>COMIC SHOP LOCATOR</p></a></li>
                    <li><a href="#"><img src="../assets/img/buy-dc-power-visa.svg" alt="cs visa"><p>DC POWER VISA</p></a></li>
                </ul>
            </section>
        </div>

    </main>
</template>

<style scoped>
.bg-black{
    background-color: #000;  
}
.bg-blue{
    background-color: dodgerblue;
}
img{
    max-width: 70px;
    max-height: 70px;
}
.main-links a{
    display: flex;
    align-items: center;
    gap: 5px;
    color: white;
}
ul{
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.main-links{
    height: 200px;
    padding: 0 50px;
    font-size: 14px;
}
.button-load{
    display: flex;
    justify-content: center;
}
.button-load a{
    color: white;
    padding: 10px 40px;
    background-color: dodgerblue;
    
}
.main-content{
    padding-bottom: 20px;
}
.jumbotron{
    background-image: url(../assets/img/jumbotron.jpg);
    height: 400px;
    position: relative;
}
.jumbotron span{
        color: white;
        padding: 8px 20px;
        background-color: dodgerblue;
        position: absolute;
        bottom: -15px;
        left: 280px;
    }
</style>
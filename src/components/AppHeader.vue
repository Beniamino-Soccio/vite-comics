<script>
export default{
    data(){
        return{

        }
    }
}
</script>

<template>
    <header>
        <a href="#"><img src="../assets/img/dc-logo.png" alt="dc-logo"></a>
        <ul class="d-flex">
            <li><a href="#">CHARACTERS</a> </li>
            <li><a href="#">COMICS</a> </li>
            <li><a href="#">MOVIES</a> </li>
            <li><a href="#">TV</a> </li>
            <li><a href="#">GAMES</a> </li>
            <li><a href="#">COLLECTIBLES</a> </li>
            <li><a href="#">VIDEO</a> </li>
            <li><a href="#">FANS</a> </li>
            <li><a href="#">NEWS</a> </li>
            <li><a href="#">SHOP</a> </li>
        </ul>
    </header>
</template>

<style scoped>
header{
    display: flex;
    justify-content: space-between;
    padding: 20px;
    font-size: 14px;
    font-weight: bold;
    height: 150px;
}
ul{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    gap: 35px;
}
ul a:hover{
    color: dodgerblue;
    
}

</style>
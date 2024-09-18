<script>

export default{
    data(){
        return{

        }
    },
    props:{
        comicUrl: {
            type: String,
            required: true,
        },
        comicPrice: {
            type: String,
            required: true,
        },
        comicSeries: {
            type: String,
            required: true,
        },
        comicType: {
            type: String,
            required: true,
        },
    }
}
</script>

<template>
    <li>
        <img :src="comicUrl" :alt="comicSeries">
        <p>

            {{ comicSeries }}
        </p>
    </li>
</template>

<style lang="scss" scoped>
img{
    width: 200px;
    height: 250px;
}
li{
    flex-basis: calc(100%/6);
    margin-bottom: 20px;
}
</style>
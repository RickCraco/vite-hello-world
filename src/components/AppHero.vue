<template>
    <div>
        <img :src="immagine" alt="">
        <h2>{{titolo}}</h2>
    </div>
</template>

<script>
    export default {
        name: "AppHero",
        data(){
            return{
                immagine: 'https://thesoundcheck.it/wp-content/uploads/2023/06/gear3-1024x576.jpg',
                titolo: 'Jumbo'
            }
        }
    }
</script>

<style lang="css" scoped>

</style>
<script>
import AppTitle from './AppTitle.vue';
    export default {
        name: 'AppHero',
        components: {
            AppTitle
        },
        data () {
            return {
                
            }
        }
    }
</script>
<template>
    <div class="hero">
        <AppTitle></AppTitle>
    </div>
</template>
<style>
    * {
        text-align: center;
    }

    .hero {
        width: 78.5%;
        height: 500px;
        background-image: url('../assets/img/purple-city.webp');
        background-size: contain;
        margin: auto;
        }
</style>
<template>
    <header>
        <Navigation />
        <Hero />    
    </header>    
</template>

<script>
import Navigation from '../Header/Navigation.vue';
import Hero from '../Header/Hero.vue';

export default {
    components: {
        Navigation,
        Hero
    }
}
</script>

<style lang="scss" scoped>
header{
    width: 100%;
    height: 100vh;
    position: relative;
    background: url('../../assets/images/burger-hero.jpg');
    background-size: cover;
    background-position: center center;
}
header::before{
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background: #000;
    opacity: .2;
}
</style>
<template>
    <div id="contact">
        <NavigationBlack />
        <Maps />
        <Contact />
        <ParallaxImg />
        <Footer />
    </div>
</template>

<script>
import Contact from '../../components/Contact/Contact.vue';
import Maps from '../../components/Contact/Maps.vue';
import ParallaxImg from '../../components/Contact/ParallaxImg.vue';
import NavigationBlack from '../../components/Header/NavigationBlack.vue';
import Footer from '../../components/Footer/Footer.vue';


export default {
    components: {
        Maps,
        Contact,
        ParallaxImg,
        NavigationBlack,
        Footer
    }
}
</script>

<style lang="scss" scoped>

</style>
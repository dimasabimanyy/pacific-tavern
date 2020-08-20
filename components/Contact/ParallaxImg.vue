<template>
    <div id="parallax-img">
        <v-parallax dark height="500" :src="require('@/assets/images/parallax-img.jpg')" :class="image">
</v-parallax>
   </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
#parallax-img{
    width: 100%;
    background: aqua;
    .image{
        object-fit: cover;
        background-size: cover;
    }
}
</style>
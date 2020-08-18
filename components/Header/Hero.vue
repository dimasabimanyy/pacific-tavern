<template>
    <div id="hero">
        <div class="hero-wrap container">
            <div class="hero-title">
                <h3>Explore and Discover</h3>
                <h1>Best Burger In Brooklyn</h1>
                <h2>LOCALLY SOURCED x CRAFTED WITH LOVE</h2>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
#hero{
    width: 100%;
    height: 85vh;
    .hero-wrap{
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        .hero-title{
            z-index: 9;
            color: $font-light;
            text-align: center;
            h3{
                font-family: $font-stack;
                font-weight: 700;
                text-transform: uppercase;
                font-size: 18px;
                margin-bottom: 1em;
            }
            h1{
                font-family: $second-font;
                font-weight: 700;
                font-size: 70px;
                line-height: 85px;
                margin-bottom: .4em;
            }
            h2{
               font-family: $font-stack;
                font-weight: 700;
                font-size: 18px; 
            }
        }
    }
}
</style>
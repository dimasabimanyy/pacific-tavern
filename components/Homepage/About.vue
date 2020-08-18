<template>
    <div id="about">
        <div class="about-wrap container">
            <h4>About Pacific Tavern</h4>
            <h1>Located in Park Slope, Pacific Tavern is a purveyor of fine American dining from the esteemed Chef Billy Lang.</h1>
            <div class="about-desc">
                <p>Pacific Tavern opened in May 2010 and is located inside the Smith Hotel Brooklyn. Since then, Golden Spork winner Chef Lang has been serving both quality interpretations of classic dishes and daring new ventures into the uncharted territories of food.</p>
                <!-- <p>Pacific Tavern's interior, designed by the award-winning Hayden Collective, reflects the hip sensibilities of the surrounding area while also paying tribute to Brooklyn's storied past. The multi-level restaurant offers the choice to observe passers-by in the glass-encased Cascade Bar on the 2nd floor, or watch the art of cooking as it occurs in the open-kitchen dining room.</p> -->
            </div>
            <div class="discover-story">
                <div class="line-story"></div>
                <a href="">
                    Discover More
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
#about{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    .about-wrap{
        width: 60%;
        margin: 0 auto;
        color: $font-dark;
        h4{
            font-size: 19px;
            font-weight: 500;
            line-height: 32px;
            font-family: $font-stack;
        }
        h1{
            font-size: 32px;
            line-height: 44px;
            font-family: $second-font;
            margin-bottom: 1em;
            margin-top: 1em;
            font-weight: 500;
        }
        .about-desc{
            margin-bottom: 2em;
            p{
                margin-bottom: 1em;
                font-size: 19px;
                line-height: 32px;
                font-family: $second-font;
            }
        }
        .discover-story{
            display: flex;
            align-items: center;
            a{
                font-family: $font-stack;
                color: $font-dark;
                font-weight: 700;
                letter-spacing: 1px;
                text-transform: uppercase;
                font-size: 15px;
                margin-left: 1em;
            }
            .line-story{
                width: 60px;
                height: 1px;
                background: $font-dark;
            }
        }
        
    }
}
</style>
<template>
    <div id="about">
        <div class="about-wrap container">
            <h4 data-aos="fade-up" data-aos-duration="1000">About Pacific Tavern</h4>
            <h1 data-aos="fade-up" data-aos-duration="1200">Located in Park Slope, Pacific Tavern is a purveyor of fine American dining from the esteemed Chef Billy Lang.</h1>
            <div class="about-desc">
                <p data-aos="fade-up" data-aos-duration="1400">Pacific Tavern opened in May 2010 and is located inside the Smith Hotel Brooklyn. Since then, Golden Spork winner Chef Lang has been serving both quality interpretations of classic dishes and daring new ventures into the uncharted territories of food.</p>
            </div>
            <!-- <div class="discover-story">
                <div class="line-story"></div>
                <a href="">
                    <h3 data-aos="fade-up" data-aos-duration="1500">Discover More</h3>
                </a>
            </div> -->
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
        color: $font-dark;
        h4{
            font-size: 17px;
            text-transform: uppercase;
            font-weight: 700;
            line-height: 32px;
            font-family: $font-stack;
        }
        h1{
            font-size: 28px;
            line-height: 44px;
            font-family: $second-font;
            margin-bottom: 1em;
            margin-top: 1em;
            font-weight: 500;
        }
        .about-desc{
            margin-bottom: 3em;
            p{
                margin-bottom: 1em;
                font-size: 19px;
                line-height: 32px;
                font-family: $second-font;
                color: rgb(0, 0, 0, 0.7);
            }
        }
        .discover-story{
            display: flex;
            align-items: center;
            a{
                font-family: 'Raleway', sans-serif;
                color: $font-dark;
                letter-spacing: 1px;
                text-transform: uppercase;
                font-size: 13px;
                line-height: 20px;
                transition: .5s ease-in-out;
            }
            .line-story{
                width: 50px;
                border: 0.5px solid $font-dark;
                background: $font-dark;
                transform: rotate(-45deg);
                transition: .5s ease-in-out;
            }
        }
        .discover-story:hover .line-story{
            transform: rotate(0deg);
        }
        .discover-story:hover a{
            margin-left: .5em;
        }
        
    }
}
</style>
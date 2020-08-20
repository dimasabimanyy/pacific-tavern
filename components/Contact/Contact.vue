<template>
    <div id="contact-info">
        <div class="contact-wrap container">
            <h5>INFORMATION</h5>
            <h1>Address and Contact</h1>
            <p class="contact-desc">Whether you have a question about our menu, location, reservation, or anything else. We are ready to answer all your questions.</p>
            <div class="icon-wrap">
                <div class="item">
                    <img src="@/assets/images/icons/location.png" alt="">
                    <h4>Address</h4>
                    <p>74 5th Avenue at St. Marks Place Brooklyn, NY 11217</p>
                </div>
                <div class="item">
                    <img src="@/assets/images/icons/contact.png" alt="">
                    <h4>Contact</h4>
                    <p>Phone : (347) 555-1234</p>
                    <p>Email : pacific@gmail.com</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
#contact-info{
    width: 100%;
    height: 100vh;
    .contact-wrap{
        height: 100%;
        text-align: center;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        h5{
            font-family: 'Raleway', sans-serif;
            color: $font-dark;
            letter-spacing: 1px;
            font-weight: 700;
            margin-bottom: 2em;
        }
        h1{
            margin-bottom: 1em;
            font-size: 35px;
            font-weight: 500;
            color: rgb(0, 0, 0, 1);
        }
        .contact-desc{
            margin-bottom: 2em;
            font-size: 19px;
            line-height: 29px;
            font-family: $second-font;
        }
        .icon-wrap{
            display: grid;
            grid-template-columns: 1fr 1fr;
            grid-gap: 5em;
            .item{
                padding: 1em;
                img{
                    margin-bottom: 1em;
                }
                h4{
                    font-family: 'Raleway', sans-serif;
                    color: #000;
                    text-align: center;
                    font-size: 19px;
                    line-height: 29px;
                    margin-bottom: 1em;
                }
                p{
                    font-size: 18px;
                    line-height: 27px;
                    font-family: $second-font;
                }
            }
        }
    }
}
</style>
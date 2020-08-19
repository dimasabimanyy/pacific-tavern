<template>
    <footer>
        <div class="footer-wrap container-fluid">
            <div class="footer-address">
                <p>PACIFIC TAVERN, 74 5TH AVENUE, BROOKLYN, NY 11217</p>
                <ul>
                    <li>
                        <a href="https://instagram.com">IG</a>
                    </li>
                    <li>
                        <a href="https://facebook.com">FB</a>
                    </li>
                    <li>
                        <a href="https://twitter.com">TW</a>
                    </li>
                </ul>
            </div>
            <div class="footer-logo">
                <img src="~/assets/images/pacific-logo.png" alt="">
            </div>
            <ul class="footer-nav">
                <nuxt-link to="/" tag="li" class="nav-link">
                    <a>Home</a>
                </nuxt-link>
                <nuxt-link to="#about" tag="li" class="nav-link">
                    <a>About</a>
                </nuxt-link>
                <nuxt-link to="#menu" tag="li" class="nav-link">
                    <a>Menu</a>
                </nuxt-link>
                <nuxt-link to="#drinks" tag="li" class="nav-link">
                    <a>Drinks</a>
                </nuxt-link>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
footer{
    background: #000;
    .footer-wrap{
        display: flex;
        padding: 4em 0;
        justify-content: space-between;
        .footer-address{
            width: 33%;
            color: rgba(255, 255, 255, 0.9);
            font-family: $font-stack;
            font-weight: 400;
            font-size: 13px;
            display: flex;
            flex-direction: column;
            // align-items: center;
            justify-content: center;
            line-height: 20px;
            p{
                margin-bottom: 1em;
            }
            ul{
                display: flex;
                list-style: none;
                li{
                    margin-right: 2em;
                    a{
                        font-size: 15px;
                        color: $font-light;
                        font-weight: 700;
                    }
                }
            }
        }
        .footer-nav{
            width: 33%;
            display: flex;
            list-style: none;
            align-items: center;
            justify-content: flex-end;
            li{
                margin-left: 2em;
            }
            a{
                color: $font-light;
                font-weight: 700;
                font-family: $font-stack;
                font-size: 15px;
                line-height: 25px;
                text-transform: uppercase;
            }
        }
        .footer-logo{
            width: 33%;
            text-align: center;
            img{
                width: 50%;
            }
        }
    }
}
</style>
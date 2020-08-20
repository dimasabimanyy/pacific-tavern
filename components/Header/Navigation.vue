<template>
    <nav>
        <div class="nav-wrap container-fluid">
            <div class="logo">
                <img src="~/assets/images/pacific-logo.png" alt="Pacific Logo">
            </div>
            <ul class="nav-links">
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
                <nuxt-link to="#reservation" tag="li" class="nav-btn">
                    <a class="btn-reservation">Reservations</a>
                </nuxt-link>
            </ul>
        </div>
    </nav>    
</template>

<style lang="scss" scoped>
    nav{
        position: relative;
        width: 100%;
        height: 15vh;
        .nav-wrap{
            display: flex;
            height: 100%;
            justify-content: space-between;
            align-items: center;
            .logo{
                z-index: 9;
                width: 150px;
                img{
                    width: 100%;
                }
            }
            .nav-links{
                z-index: 9;
                display: inline-flex;
                list-style: none;
                align-items: center;
                .nav-link, .nav-btn{
                    margin-left: 2.5em;
                    a{
                        text-transform: uppercase;
                        color: $font-light;
                        font-family: $font-stack;
                        font-size: 15px;
                        font-weight: 700;
                    }
                }
                .nav-link a:hover{
                    color: #e4e4e4;
                }
            }
        }
    }
    .btn-reservation{
        padding: .9em 1.7em;
        background: #B5A46D;
        transition: .3s ease-in;
    }
    .btn-reservation:hover{
        color: !important #fff;
        background: $font-dark;
    }
</style>
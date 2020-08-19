<template>
    <div id="drinks-pricing">
        <div class="drinks-wrapper">
            
            <div class="menu-logo">
                <img src="~/assets/images/pacific-logo.png" alt="">
            </div>

            <div class="menu-wrapper">
                <h3 class="menu-title">DRINKS</h3>
                <div class="menu-list">
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Primavera Salad</h4>
                            <div class="menu-price">$8</div>
                        </div>
                        <p class="menu-desc">arugula, cherry tomato, shaved almonds, shallot vinaigrette</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Grilled Calamari</h4>
                            <div class="menu-price">$12</div>
                        </div>
                        <p class="menu-desc">tomato sauce, lemon</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Mac and Cheese</h4>
                            <div class="menu-price">$13</div>
                        </div>
                        <p class="menu-desc">cheddar, gruyere, gouda, truffle oil</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Grilled Calamari</h4>
                            <div class="menu-price">$12</div>
                        </div>
                        <p class="menu-desc">tomato sauce, lemon</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Mac and Cheese</h4>
                            <div class="menu-price">$13</div>
                        </div>
                        <p class="menu-desc">cheddar, gruyere, gouda, truffle oil</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Grilled Calamari</h4>
                            <div class="menu-price">$12</div>
                        </div>
                        <p class="menu-desc">tomato sauce, lemon</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Mac and Cheese</h4>
                            <div class="menu-price">$13</div>
                        </div>
                        <p class="menu-desc">cheddar, gruyere, gouda, truffle oil</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Grilled Calamari</h4>
                            <div class="menu-price">$12</div>
                        </div>
                        <p class="menu-desc">tomato sauce, lemon</p>
                    </div>
                    <div class="menu-item">
                        <div class="menu-sub-title">
                            <h4>Mac and Cheese</h4>
                            <div class="menu-price">$13</div>
                        </div>
                        <p class="menu-desc">cheddar, gruyere, gouda, truffle oil</p>
                    </div>
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
#drinks-pricing{
    width: 100%;
    position: relative;
    background: url('../../assets/images/drinks-bg.jpg');
    background-size: cover;
    background-position: center;
    padding: 7em 0;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    .drinks-wrapper{
        width: 80%;
        margin: 0 auto;
        .menu-logo{
        width: 250px;
        margin: 0 auto;
        margin-bottom: 3em;
            img{
                z-index: 9;
                width: 100%;
            }
        }
        .menu-wrapper{
            margin-bottom: 1em;
            .menu-title{
                text-align: center;
                font-family: $font-stack;
                font-size: 17px;
                margin-bottom: 2em;
                margin-top: 2em;
                color: $font-light;
            }
            .menu-list{
                display: grid;
                grid-gap: 1em;
                grid-template-columns: 1fr 1fr 1fr;
                .menu-item{
                    -webkit-box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                    -moz-box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                    box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                    padding: 1em;
                    transition: .3s ease-in-out;
                    .menu-sub-title{
                        display: flex;
                        justify-content: space-between;
                        margin-bottom: .5em;
                        color: $font-light;
                        h4{
                            font-size: 17px;
                            line-height: 24px;
                            font-family: $font-stack;
                            font-weight: 700;
                        }
                        .menu-price{
                            font-weight: 700;
                            font-family: $second-font;
                        }
                    }
                    .menu-desc{
                        font-family: $font-stack;
                        font-weight: 400;
                        font-size: 17px;
                        line-height: 25px;
                        color: $font-light;
                    }
                }
                .menu-item:hover{
                    box-shadow: none;
                }
            }
        }  
    }
}
</style>
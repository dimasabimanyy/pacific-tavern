<template>
    <div id="menu" class="container-md">
        <div class="menu-logo">
            <img src="~/assets/images/pacific-dark.png" alt="">
        </div>
        
        <div class="menu-wrapper">
            <div class="menu-title">
                <div class="line-story"></div>
                <h3>SNACK x SALAD</h3>
            </div>
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
            </div>
        </div>

        <div class="menu-wrapper">
            <div class="menu-title">
                <div class="line-story"></div>
                <h3>SANDWICHES</h3>
            </div>
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
            </div>
        </div>

        <div class="menu-wrapper">
            <div class="menu-title">
                <div class="line-story"></div>
                <h3>MAINS</h3>
            </div>
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
            </div>
        </div>

    </div>
</template>

<style lang="scss" scoped>
#menu{
    padding: 7em 0;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    .menu-logo{
        width: 300px;
        margin-bottom: 3em;
        img{
            width: 100%;
        }
    }
    .menu-wrapper{
        margin-bottom: 2em;
        .menu-title{
            display: flex;
            justify-content: center;
            align-items: center;
            .line-story{
                width: 50px;
                border: 0.5px solid rgba(0,0,0,0.7);
                // background: $font-dark;
                transition: .5s ease-in-out;
            }
            h3{
                margin-left: 1em;
                text-align: center;
                font-family: $font-stack;
                font-size: 17px;
                margin-bottom: 2em;
                margin-top: 2em;
                color: rgba(0,0,0,0.7);
            }
        }
        .menu-list{
            display: grid;
            grid-gap: 1.5em;
            grid-template-columns: 1fr 1fr 1fr;
            .menu-item{
                // -webkit-box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                // -moz-box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                // box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                padding: 1em;
                // border: 1px solid #ccc;
                transition: .3s ease-in-out;
                border-radius: 3px;
                .menu-sub-title{
                    display: flex;
                    justify-content: space-between;
                    margin-bottom: .5em;
                    h4{
                        font-size: 17px;
                        line-height: 24px;
                        color: rgba(0,0,0,0.7);
                        font-family: $font-stack;
                    }
                    .menu-price{
                        color: rgba(0,0,0,0.7);
                        font-family: $second-font;
                    }
                }
                .menu-desc{
                    font-family: $font-stack;
                    font-weight: 400;
                    font-size: 17px;
                    line-height: 25px;
                    color: rgba(0,0,0,0.6);
                }
            }
            .menu-item:hover{
                -webkit-box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                -moz-box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
                box-shadow: 4px 6px 10px .5px rgba(0,0,0,0.1);
            }
        }

    }
}
</style>
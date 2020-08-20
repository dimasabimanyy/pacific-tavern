<template>
    <div id="reservation" class="container">
        <h1 class="reservation-title">
            A Journey to meet the Thelma Winery. Come to visit us!
        </h1>
        <a href="">
            <button class="btn-book-now">
                BOOK NOW
            </button>
        </a>
        <div class="reservation-info">
            <p>Call (347) 555–1234 from 5a – 11p daily, or book online with OpenTable.</p>
            <p>Reservations required for parties of 6 or more.</p>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
#reservation{
    padding: 7em 0;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    .reservation-title{
        font-size: 50px;
        line-height: 60px;
        font-weight: 500;
        margin-bottom: .5em;
        font-family: $second-font;
    }
    .btn-book-now{
        padding: 1.5em 3em;
        background: #000;
        color: $font-light;
        font-family: $font-stack;
        font-weight: 700;
        font-size: 14px;
        margin-bottom: 3em;
        transition: .3s ease-in;
    }
    .btn-book-now:hover{
        background: #B5A46D;
    }
    .reservation-info{
        p{
            font-size: 15px;
            line-height: 23px;
            margin-bottom: .4em;
            color: rgb(148, 148, 148, 0.8);
            font-family: $font-stack;
        }
    }
}
</style>
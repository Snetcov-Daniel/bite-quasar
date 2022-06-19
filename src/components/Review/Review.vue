<template>
    <div class="review row items-center justify-between">
        <div class="review__info">
            <h3 class="review__info-title">Hey. You make us smile, too!</h3>
            <p class="review__info-text">
                We believe in oral care products that are better for you, and the planet. Every product we make is
                thoughtfully formulated to keep you smiling bright.
            </p>
            <a href="" class="review__info-link">See more reviews</a>
        </div>
        <div class="review__circle"></div>
        <div class="review__comment">
            <p class="review__comment-motto">
                Easiest and most effective whitener I've tried
            </p>
            <p class="review__comment-text">
                My teeth are very prone to being yellow from medications, and the only whitening that would really do
                anything was Smile Sciences. This Bite..."
            </p>
            <p class="review__comment-subscription">Katie S. · Whitening Gel - Subscription</p>
        </div>
        <div class="review__circle"></div>
    </div>
</template>

<script>
export default {
    name: 'Review',

    data() {
        return {
            
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style lang="scss" scoped>









.review {
    padding: 130px 200px;
    color: #172345;
}
.review__info {
    max-width: 457px;
    margin-bottom: 11px;
}
.review__info-title {
    font-weight: 400;
    font-size: 56px;
    line-height: 53px;
    letter-spacing: 3.28981px;
}
.review__info-text {
    font-size: 24px;
    line-height: 49px;
    letter-spacing: 1.31px;
    margin-bottom: 20px;
}
.review__info-link {
    font-size: 22px;
    line-height: 39px;
    color: #0038D2;
    text-decoration: none;
}
.review__circle {
    width: 50px;
    height: 50px;
    background: #FFFFFF;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.5);
    border-radius: 50%;
}
.review__comment {
    max-width: 295px;
    padding-top: 83px;
    color: #415286;
    text-align: center;
}
.review__comment-motto {
    max-width: 234px;
    font-size: 15px;
    line-height: 33px;
    margin: 0 auto;
}
.review__comment-text {
    font-size: 21px;
    line-height: 33px;
    margin-bottom: 55px;
}
.review__comment-subscription {
    font-size: 12px;
    line-height: 21px;
    color: #000;
    text-transform: uppercase;
}
</style>
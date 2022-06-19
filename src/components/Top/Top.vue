<template>
    <div class="top">
        <app-header />
        <div class="top__info">
            <h1 class="top__info-title">Toothpaste, reinvented</h1>
            <p class="top__info-text">
                The only plastic-free and clean way to replace the paste you've used your whole life.
            </p>
            <a href="" class="top__info-btn">shop now</a>
        </div>
        <div class="top__sponsors">
            <a href="" class="top__sponsor"><img src="../../img/seen.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/forbes.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/oprah.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/cosmopolitan.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/people.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/buzzfeed.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/women-health.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/now.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/insider.png" alt=""></a>
            <a href="" class="top__sponsor"><img src="../../img/country-living.png" alt=""></a>
        </div>
    </div>
</template>

<script>

import Header from './Header';

export default {
    name: 'Top',
    components: {
        appHeader: Header,
    },
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
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
ul {
    list-style: none;
}
a {
    text-decoration: none;
}
.top {
    position: relative;
    width: 100%;
    height: 100vh;
    color: #fff;
    font-family: 'Roboto', sans-serif;
    text-align: center;
    padding-top: 250px;
    background-image: url('../../img/header-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
.top__info {
    padding: 0 15px;
}
.top__info-title {
    max-width: 720px;
    font-size: 62px;
    line-height: 70px;
    letter-spacing: 4.38641px;
    margin: 0 auto 21px;
}
.top__info-text {
    max-width: 599px;
    font-size: 29px;
    line-height: 42px;
    margin: 0 auto 27px;
}
.top__info-btn {
    display: inline-block;
    color: #4144BF;
    padding: 13px 34px;
    background-color: #fff;
    border: 3px solid #4144BF;
    border-radius: 50px;
}
.top__sponsors {
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 74px;
    background-color: #DEE6F3;
}
.top__sponsor {
    margin: 0 30px;
}

</style>
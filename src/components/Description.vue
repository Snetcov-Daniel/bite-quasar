<template>
    <div class="description">
        <div class="row">
            <div class="col-5"><q-separator color="#D3E1E6" class="description__separator"/></div>
            <div class="col-2"></div>
            <div class="col-5"><q-separator color="#D3E1E6" class="description__separator"/></div>
        </div>
        <q-btn class="absolute-center description__shop-all" color="primary" rounded label="Shop all products"/>
        <div class="row description__slider">
            <div class="col flex justify-end vertical-middle description__slider-left">
                <q-img src="../../src/img/description-photo.png" alt="Description image" class="flex-center description__slider-left__image">
                    <div class="absolute-bottom text-center text-h3 description__slider-left__text">Meet Lindsay and learn more about Bite</div>
                    <q-btn size="20px" no-caps outline style="background-color: #FFFFFF !important;" rounded color="primary" label="Learn more!" class="absolute-bottom description__learn-more"/>
                </q-img>
            </div>
            <div class="col description__slider-right">
                <q-carousel
                    v-model="slide"
                    transition-prev="scale"
                    transition-next="scale"
                    swipeable
                    animated
                    control-color="black"
                    navigation-icon="square"
                    navigation-active-icon="square"
                    navigation
                    padding
                    height="100%"
                    class="bg-white rounded-borders description__slider-right__carousel"
                >
                    <div class="flex-center get-started">
                        Get started — from $7.50/month
                    </div>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                    <q-carousel-slide name="style" class="column no-wrap flex-center">
                        <q-img src="../../src/img/fast-company-logo.png"/>
                        <div class="q-mt-md text-h2 text-center carousel-text">
                            "The Most Creative People in Business 2020"
                        </div>
                    </q-carousel-slide>
                </q-carousel>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Description",
    data () {
        return {
            slide: 'style',
            lorem: 'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaque voluptatem totam, architecto cupiditate officia rerum, error dignissimos praesentium libero ab nemo.'
        }
    }
}
</script>

<style scoped>
    .description__separator {
        margin-top: 20px;
        height: 5px;
    }
    .description__shop-all {
        position: relative;
        margin-top: 35px;
    }
    .description__slider-left__image {
        width: 95%;
    }
    .description__slider-left__text {
        background: none;
        margin: auto;
        margin-bottom: 130px;
        width: 60%;
    }
    .description__learn-more {
        width: 30%;
        margin: auto;
        margin-bottom: 64px;
        padding: 5px 0;
    }
    .description__slider-right {
        text-align: center;
        display: flex;
        justify-content: center;
    }
    .carousel-text {
        color: #172345;
    }
    .get-started {
        position: relative;
        bottom: -350px;
        z-index: 2000;
        margin: auto;
        font-family: 'Roboto', sans-serif;
    }
</style>

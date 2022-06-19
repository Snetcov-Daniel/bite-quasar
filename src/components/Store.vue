 <template>
    <div class="store row flex wrap justify-between align-center">
        <product-card class="big-card col-4" v-for="(product, index) in firstRow" :key="index"
            :productName="product.name" :productPrice="product.price" :productType="product.type"
            :productRating="product.rating" :productReviews="product.reviews" :src="product.img"></product-card>
        <product-card class="small-card col col-md-3" v-for="(product, index) in secondRow" :key="index"
            :productName="product.name" :productPrice="product.price" :productType="product.type"
            :productRating="product.rating" :productReviews="product.reviews" :src="product.img"></product-card>
    </div>
</template>

<script>

import ProductCardVue from './ProductCard.vue'

export default {
    name: "Store",
    components: {
        productCard: ProductCardVue
    },
    data() {
        return {
            firstRow: [
                {
                    name: "Fresh Mint",
                    price: 30,
                    type: "Toothpaste",
                    rating: 4.9,
                    reviews: 10368,
                    img: require("assets/freshMint.png")
                },
                {
                    name: "Mouthwash Bits",
                    price: 20,
                    type: "Bits",
                    rating: 5,
                    reviews: 366,
                    img: require("assets/mouthWashBits.png")
                },
                {
                    name: "Whitening Gel",
                    price: 24,
                    type: "Gel",
                    rating: 5,
                    reviews: 18,
                    img: require("assets/whiteningGel.png")
                },
                {
                    name: "Dental Floss",
                    price: 12,
                    type: "Floss",
                    rating: 4.9,
                    reviews: 256,
                    img: require("assets/dentalFloss.png")
                },
                {
                    name: "Bamboo Toothbrush",
                    price: 12,
                    type: "Toothbrush",
                    rating: 4.9,
                    reviews: 962,
                    img: require("assets/bambooToothbrush.png")
                },
                {
                    name: "Daily Habits Kit",
                    price: 60,
                    type: "Kit",
                    rating: 5,
                    reviews: 16144,
                    img: require("assets/dailyHabitsKit.png")
                }
            ],
            secondRow: [
                {
                    name: "Fresh Mint",
                    price: 12,
                    type: "Toothpaste",
                    rating: 4.9,
                    reviews: 10368,
                    img: require("assets/freshMint2.png")
                },
                {
                    name: "Mint Charcoal        ",
                    price: 12,
                    type: "Toothpaste",
                    rating: 4.8,
                    reviews: 6318,
                    img: require("assets/mintCharcoal.png")
                },
                {
                    name: "Berry Twist",
                    price: 12,
                    type: "Toothpaste",
                    rating: 4.9,
                    reviews: 607,
                    img: require("assets/berryTwist.png")
                },
                {
                    name: "The Duo",
                    price: 12,
                    type: "Toothpaste",
                    rating: 4.8,
                    reviews: 5752,
                    img: require("assets/theDuo.png")
                },
            ]
        }
    },
}
</script>

<style lang="scss" scoped>
.big-card {
    width: 600px;
    height: auto;
    margin: 50px 20px;
}

.small-card {
    width: 400px;
    height: auto;
    margin: 50px 20px
}
</style>
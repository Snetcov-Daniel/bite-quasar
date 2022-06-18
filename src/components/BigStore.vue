<template>
    <div class="big-store row">
        <div v-for="(product, index) in products" :key="index">
            <product-card :productName="product.name" :productPrice="product.price" :productType="product.type" :productRating="product.rating" :productReviews="product.reviews"></product-card>
        </div>
    </div>
</template>

<script>

import ProductCardVue from './ProductCard.vue'

export default {
    name: "BigStore",
    components: {
        productCard: ProductCardVue
    },
    data() {
        return {
            products: [
                {
                    name: "Fresh Mint",
                    price: 30,
                    type: "Toothpaste",
                    rating: 4.9,
                    reviews: 10368
                },
                {
                    name: "Mouthwash Bits",
                    price: 20,
                    type: "Bits",
                    rating: 5,
                    reviews: 366
                },
                {
                    name: "Whitening Gel",
                    price: 24,
                    type: "Gel",
                    rating: 5,
                    reviews: 18
                },
                {
                    name: "Dental Floss",
                    price: 12,
                    type: "Floss",
                    rating: 4.9,
                    reviews: 256
                },
                {
                    name: "Bamboo Toothbrush",
                    price: 12,
                    type: "Toothbrush",
                    rating: 4.9,
                    reviews: 962
                },
                {
                    name: "Daily Habits Kit",
                    price: 60,
                    type: "Kit",
                    rating: 5,
                    reviews: 16144
                },
            ]
        }
    }
}
</script>

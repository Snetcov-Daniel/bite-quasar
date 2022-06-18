<template>
    <q-card class="product-card">
        <img :src="src">
        <q-card-section>
            <div class="text-h4">{{ productName }}</div>
            <div class="text-subtitle2">{{ productPrice }}$</div>
        </q-card-section>
        <div class="text-h6">{{ productType }}</div>
        <q-card-section>
            <div class="text-h4">Rated {{ productRating }} out of 5</div>
            <div class="text-h4">{{ productReviews }}Reviews</div>
        </q-card-section>
        <img src="../assets/img/stars.svg">
    </q-card>
</template>

<script>
export default {
    name: "ProductCard",
    props: {
        src: String,
        productName: String,
        productPrice: Number,
        productType: String,
        productRating: Number,
        productReviews: Number
    },
    data() {
        return {}
    }
}
</script>

<template>
    <q-card class="product-card">
        <img :src="src">
        <q-card-section class="flex justify-between">
            <div class="text-h4">{{ productName }}</div>
            <div class="text-h4">${{ productPrice }}</div>
        </q-card-section>
        <q-card-section>
                <div class="text-h6 text-grey-13">{{ productType }}</div>
        </q-card-section>
        <q-card-section class="flex q-gutter-xl">
            <div class="text-h6">Rated {{ productRating }} out of 5</div>
            <div class="text-h6">{{ productReviews }} Reviews</div>
        </q-card-section>
        <img src="../assets/stars.svg" class="stars">
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

<style lang="scss" scoped>

    .stars {
        width: 150px;
        height: 30px;
    }
</style>svgsvg
<template>
    <div class="get-started">
        <div class="started-header">
            <div class="text-h3 header-title">
                We make your daily routine more sustainable with products that are plastic-free, cruelty-free and made with clean ingredients.
            </div>
            <div class="text-h5 header-desc1 text-uppercase">
                Plastic-free | Cruelty-free | Clean ingredients
            </div>
        </div>
        <div class="row started-info">
            <div class="col-2 started-start">
                <div class="text-h5 text-center start-title">
                    Meet the future of oral care.
                </div>
                <q-btn outline color="primary" rounded label="Get started" no-caps class="text-center start-btn"/>
            </div>
            <div class="col-3 started-product">
                <img src="../img/started1.png" class="product-img" alt="">
                <div class="text-h6 text-center product-title">
                    Toothpaste Bits
                </div>
                <div class="text-h6 text-center product-price">
                    From $7.50 / month
                </div>
            </div>
            <div class="col-3 started-product">
                <img src="../img/started2.png" class="product-img" alt="">
                <div class="text-h6 text-center product-title">
                    Mouthwash Bits
                </div>
                <div class="text-h6 text-center product-price">
                    From $5.00 / month
                </div>
            </div>
            <div class="col-3 started-product">
                <img src="../img/started3.png" class="product-img" alt="">
                <div class="text-h6 text-center product-title">
                    Whitening Gel
                </div>
                <div class="text-h6 text-center product-price">
                    From $5.00 / month
                </div>
            </div>
            <div class="col-1">

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Get-started"
}
</script>

<style scoped>
    .started-header {
        margin: 31px 0 23px 0;
    }
    .header-title {
        font-size: 24px;
        font-family: 'Roboto', sans-serif;
        color: #172345;
        width: 800px;
        text-align: center;
        margin: auto;
        line-height: 39px;
        letter-spacing: 1.31592px;
    }
    .header-desc1 {
        color: #172345;
        font-family: 'Roboto';
        font-size: 13px;
        line-height: 17px;
        text-align: center;
        font-weight: 400;
        margin: auto;
        letter-spacing: 2.08354px
    }
    .started-info {
        margin: 52px 15px 200px;
        height: 450px;
    }
    .started-start {
        width: 16.6667%;
        display: flex;
        align-items: center;
        flex-direction: column;
        height: 250px;
        margin: auto;
    }
    .start-title {
        width: 40%;
    }
    .start-btn {
        margin: auto;
        padding: 5px;
    }
    .product-img {
        width: 100%;
    }
    .product-title {
        margin-top: -100px;
        font-size: 23px;
        font-weight: 400;
        line-height: 36px;
        font-family: 'Roboto', sans-serif;
    }
    .product-price {
        font-weight: 400;
        font-size: 14px;
        font-family: 'Roboto', sans-serif;
        line-height: 25px;
        text-transform: uppercase;
    }
</style>

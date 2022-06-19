<template>
    <div class="footer">
        <a href="" class="footer__logo"><img src="../../img/logo.png" alt=""></a>
        <div class="footer__content row">
            <footer-list :listTitle="listTitles[0]" :listItems="subscriptions" />
            <footer-list :listTitle="listTitles[1]" />
            <footer-list :listTitle="listTitles[2]" :listItems="singleBottles" />
            <footer-list :listTitle="listTitles[3]" :listItems="essentials" />
            <footer-list :listTitle="listTitles[4]" :listItems="aboutUs" />
            <div class="footer__content-item">
                <h4 class="footer__content-item-title footer-list-title">Press</h4>
                <ul class="footer__content-item-list footer-list">
                    <li><a href="">Past press</a></li>
                </ul>
                <h4 class="footer__content-item-title footer-list-title">For press or media inquiries, please email</h4>
            </div>
            <div class="footer__content-item">
                <h4 class="footer__content-item-title footer-list-title">Need help?</h4>
                <ul class="footer__content-item-list footer-list">
                    <li>Check out our <a href="">help center</a></li>
                </ul>
                <p class="footer-list-subtitle">Need further assistance? Contact us</p>
                <a href="" class="footer-email">hello@bitetoothpastebits.com</a>
            </div>
        </div>
        <div class="footer__copy">
            Copyright © 2021, <a href="">Bite</a>. <a href="">Powered by Shopify</a>
            <img src="../../img/footer-icon.png" alt="" class="footer__copy-img">
        </div>
        <ul class="footer__rules row justify-center">
            <li><a href="">Accessibility Statement</a></li>
            <li><a href="">Privacy policy</a></li>
            <li><a href="">Terms of service</a></li>
        </ul>
    </div>
</template>

<script>

import FooterList from "./FooterList";

export default {
    name: 'Footer',
    components: {
        footerList: FooterList,
    },
    data() {
        return {
            listTitles: ['Subscriptions', 'Follow us', 'Single Bottles', 'The Essentials', 'About Us'],
            subscriptions: ['The Fresh Mint Club', 'The Berry Twist Club', 'Fresh Mint with Activated Charcoal'],
            singleBottles: ['Fresh Mint', 'The Duo', 'Mint Charcoal', 'Berry Twist Toothpaste Bits'],
            essentials: ['The Fresh Mint Club', 'The Duo', 'Mouthwash', 'Floss, by Bite', 'Brush, by Bite'],
            aboutUs: ['Who we are', 'Read the reviews', 'Sustainability + Packaging', 'Our ingredients', 'The Good Bits (our blog)', 'FAQ'],
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style lang="scss" scoped>






.footer {
    padding: 30px 200px 114px;
    background-color: #FDF8F5;
}
.footer__logo {
    display: inline-block;
    margin-bottom: 20px;
}

.footer__content {
    margin-bottom: 50px;
}
.footer__content-item {
    width: 25%;
    min-width: 285px;
    padding-right: 20px;
    margin-bottom: 20px;
    box-sizing: border-box;
}
.footer-list-title {
    font-size: 23px;
    line-height: 32px;
    font-weight: 400;
    color: #172345;
    margin: 0 0 11px;
}
.footer-list {
    padding: 0;
    list-style: none;
    font-size: 18px;
    line-height: 31px;
    li {
        margin-bottom: 5px;
    }
    a {
        color: #6C77B5;
        text-decoration: none;
    }
}
.footer-list-subtitle {
    font-size: 14px;
    line-height: 31px;
}
.footer-email {
    font-size: 18px;
    line-height: 31px;
    color: #6C77B5;
    text-decoration: none;
}
.footer__copy {
    text-align: center;
    margin-bottom: 30px;
    a {
        color: #6C77B5;
        text-decoration: none;
    }
    img {
        display: block;
        padding-top: 20px;
        margin: 0 auto;
    }
}

.footer__copy-img {
    text-align: center;
}

.footer__rules {
    padding: 0;
    list-style: none;
    li {
        margin: 0 21px;
    }
    a {
        color: #6C77B5;
        text-decoration: none;
    }
}
</style>
<template>
    <div class="footer__content-item">
        <h4 class="footer__content-item-title footer-list-title">{{ listTitle }}</h4>
        <ul class="footer__content-item-list footer-list">
            <li v-for="(item, index) in listItems" :key="index"><a href="">{{ item }}</a></li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'FooterList',
    props: {
        listTitle: String,
        listItems: Array
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
</style>
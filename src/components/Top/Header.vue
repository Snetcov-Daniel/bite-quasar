<template>
    <q-header class="header">
        <q-toolbar class="header__inner row justify-between content-center">
            <ul class="header__menu row">
                <li class="header__menu-item"><a href="">shop</a></li>
                <li class="header__menu-item"><a href="">about us</a></li>
                <li class="header__menu-item"><a href="">sustainability</a></li>
            </ul>
            <a href="" class="header__logo absolute-center"><img src="../../img/logo.png" alt=""></a>
            <div class="header__icons">
                <a href="" class="header__icon"><img src="../../img/cart-icon.png" alt=""></a>
                <a href="" class="header__icon"><img src="../../img/profile-icon.png" alt=""></a>
            </div>
        </q-toolbar>
    </q-header>
</template>

<script>
export default {
    name: 'Header',

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
.header {
    width: 100%;
    height: 72px;
    padding: 0 42px;
    background-color: transparent;
    &__inner {
        height: 100%;
    }
}
.header__menu-item {
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-right: 40px;
    &:last-child {
        margin-right: 0;
    }
    a {
        color: #5326D4;
    }
}
.header__icon {
    margin-right: 50px;
    &:last-child {
        margin-right: 0;
    }
}
</style>
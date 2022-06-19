<template>
    <q-layout hHh lpr fff>
        <top/>
        <q-page-container>
            <router-view />
        </q-page-container>
        <Footer/>
    </q-layout>
</template>

<script>

import Top from "../components/Top/Top";
import Footer from "../components/Footer/Footer";

export default {
    name: 'MainLayout',
    components: {
        top: Top,
        Footer: Footer
    },
    data () {
        return {

        }
    }
}
</script>

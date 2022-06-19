<template>
    <q-layout hHh lpr fff>
        <top/>
        <q-page-container>
            <!-- <router-view /> -->
            <review/>
        </q-page-container>
        <Footer/>
    </q-layout>
</template>

<script>

import Top from "../components/Top/Top";
import Review from "../components/Review/Review";
import Footer from "../components/Footer/Footer";

export default {
    name: 'MainLayout',
    components: {
        top: Top,
        review: Review,
        Footer: Footer
    },
    data () {
        return {
            
        }
    }
}
</script>

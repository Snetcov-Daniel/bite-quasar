<template>
    <q-layout hHh lpr fff>
        <q-header reveal bordered>

        </q-header>
        <q-page-container>
            <router-view />
        </q-page-container>
        <q-footer reveal bordered>

        </q-footer>
    </q-layout>
</template>

<script>

export default {
    name: 'MainLayout',
    components: {

    },
    data () {
        return {

        }
    }
}
</script>

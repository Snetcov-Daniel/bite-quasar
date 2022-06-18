<template>
    <q-page>
        <big-store></big-store>
    </q-page>
</template>

<script>

import BigStoreVue from 'src/components/BigStore.vue'

export default {
    name: 'PageIndex',
    components: {
        bigStore: BigStoreVue
    }
}
</script>

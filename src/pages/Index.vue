<template>
    <q-page>
        <get-started/>
        <description/>
    </q-page>
</template>

<script>
import Description from '../components/Description'
import GetStarted from '../components/Get-started'

export default {
    name: 'PageIndex',
    components: {
        description: Description,
        getStarted: GetStarted
    }
}
</script>

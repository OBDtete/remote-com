<template>
    <div>
        <h2>ComponentC</h2>
            <componentE />
    </div>
</template>

<script>
    import componentE from './componentE.vue'
    export default {
        name: 'componentC',
        components: {
            componentE
        }
    }
</script>

<style scoped>

</style>
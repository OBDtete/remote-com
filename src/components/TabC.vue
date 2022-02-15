<template>
    <div>
        Tab C Content
        <input type="text" v-model="firstName" placeholder="Input Name">
    </div>
    
</template>

<script>
    export default {
        name: 'TabC',
        data(){
            return{
                firstName: ''
            }
        }
    }
</script>

<style>

</style>
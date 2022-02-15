<template>
    <div>
        <h2>This is a Popup</h2>
        <button @click="$emit('close', name)">Close Popup</button>
        <input type="text" v-model="name">
    </div>
</template>

<script>
    export default {
        name: 'Popup',
        emits: {
            close: (name) => {
                if(!name) {
                    return false
                }else{
                    return true
                }
            }
        },
        data(){
            return {
                name: ''
            }
        }
    }
</script>

<style scoped>

</style>
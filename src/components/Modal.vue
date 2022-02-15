<template>
    <div class="modal-overlay" @click="$emit('close')">
        <div class="modal-content">
            <slot></slot>
            <hr/>
            <button @click="$emit('close')"> Close modal</button>
        </div>

    </div>
</template>

<script>
    export default {
        name: 'Modal',
        emits: ['close']
    }
</script>

<style scoped>

</style>
<template>
    <div>
        <input type="text" :value="modelValue" @input="$emit('update:modelValue', $event.target.value)" />
    </div>
</template>

<script>
    export default {
        name: "Input",
        props: {
            modelValue : String
        }
    }
</script>

<style scoped>
    input[type ="text"]{

        width: 400px;
        color: chartreuse;
    }
</style>
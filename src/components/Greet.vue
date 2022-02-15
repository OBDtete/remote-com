<template>
    <h2>Hello {{name}} you are {{degree}}</h2>
</template>

<script>
    export default {
       name: 'Greet', 
       props:['name', 'degree', 'salam'],
                
    };
</script>

<style scoped>

</style>



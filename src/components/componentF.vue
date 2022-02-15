<template>
    <div>
        <h2>ComponentF</h2>
        <h3>USERNAME in componentF is  : {{username}}</h3>
        
    </div>
</template>

<script>
    
    export default {
      name: 'componentF',
      inject : ['username']
      

    }
</script>

<style scoped>

</style>
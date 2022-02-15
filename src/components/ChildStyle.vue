<template>
    <div>
        <slot></slot>
        <slot name="OBD"></slot>
    </div>
</template>

<script>
    export default {
      name: 'ChildStyle'  
    }
</script>

<style scoped>
    h4{
  color: olivedrab;
}
</style>
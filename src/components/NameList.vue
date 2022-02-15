<template>
    <div>
       <h3 v-for="name in names" :key="name.firstName">
           <slot :firstName="name.firstName" :lastName="name.lastName" ></slot>
       </h3>
    </div>
</template>

<script>
    export default {
        name: 'NameList',
        data(){
            return{
                names: [
                    {   firstName : 'clark',
                        lastName   : 'hommar'
                    },
                    {   firstName : 'steev',
                        lastName  : 'obd'
                    },
                    {
                        firstName : 'princiese',
                        lastName  :  'daina'
                    }

                ]
            }
        }
    
    }
</script>

<style scoped>

</style>
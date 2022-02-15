<template>
    <div>
        
        <h2>Article Component</h2>
        <h2 v-bind="$attrs">Title : {{title}}</h2>
        <h2>Likes : {{likes}}</h2>
        <h2>Ispublished : {{isPublished ? 'yes' :  'no'}}</h2>
    </div>
</template>

<script>
    export default {
        name: 'Article',
        props: {
            title: {
                type: String,
                required:true,
                default: 'Article Default title'


            },
            likes: Number,
            isPublished: Boolean


        },
        inheritAttrs: false  
    }
</script>

<style scoped>

</style>


<template>
    <button @click="onClick()":style="{background:color}" class="btn">{{ task }}</button>
</template>

<script>
    export default{
        name:'Button',
        props:{
            task:String,
            color: String
        },
        methods:{
            onClick(){
                console.log('clicked')
            }
        }
    }
</script>
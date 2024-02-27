<template>
    <div :key="task.id" v-for="task in tasks">{{ task.name }}</div>
</template>

<script>
    export default{
        name:'Tasks',
        props:{
            tasks:Array
        }
    }
</script>
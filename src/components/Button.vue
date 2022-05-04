<template>
    <button>{{ ButtonText }}</button>
</template>

<script>
    export default{
        name: 'Button',
        props:{
            ButtonText:{
                type: String,
                default:"TestButton"
            } 
        }
    }
</script>
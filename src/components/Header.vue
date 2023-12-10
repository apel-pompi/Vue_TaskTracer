<template>
    <header>
        <h1>Task Tracer</h1>
        <Button text="Add Tast" color="green"></Button>
    </header>
</template>

<script>
    import Button from "./Button";
    export default{
        name:'Header',
        components:{
            Button
        },
    }
</script>

<style scoped>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
</style>
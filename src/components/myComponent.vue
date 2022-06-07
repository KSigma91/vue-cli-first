<template>
    <div class="container">
        <h1>La mia prima app con Vue CLI!</h1>
    </div>
</template>

<script>
    export default {
        name : 'myComponent',
        props : {
            msg : String
        }
    }
</script>

<style scoped>
    h1 {
        margin: 40px 0 0;
        color: deepskyblue;
    }
</style>
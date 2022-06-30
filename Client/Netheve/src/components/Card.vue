<script>
    export default{
        props: ['title']
    }
</script>

<template>
    <div class="card-wrapper">
        <span>{{title}}</span>
    </div>
</template>

<style>
    .card-wrapper
    {
        height: 12rem;
        width: 9rem;
        background-color: aqua;
    }
</style>
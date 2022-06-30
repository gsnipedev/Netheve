<script setup>
    import Card from "./Card.vue"
    import { ref } from 'vue'
    const products = ref([
    {id: 0, name: 'shirt'},
    {id: 1, name: 'jacket'},
    {id: 2, name: 'shoes'}
    ])
</script>

<template>
    <section>
        <div class="content-wrapper">
            <div>
                halo
            </div>
            <div>
                <div v-for="(product, index) in products">
                    <Card title=" {{product.id}}"/>
                </div>
            </div>
            <div>
                Guys
            </div>
        </div>
    </section>
</template>

<style>
    .content-wrapper{
        display: grid;
        grid-template-rows: 1;
        grid-template-columns: 3;
        gap: 10px;
    }
    .content-wrapper > :nth-child(1){
        grid-column: 1;
        grid-row: 1;
    }
    .content-wrapper > :nth-child(2)
    {
        grid-column: 2;
        grid-row: 1;
        background-color: rebeccapurple;
        display: flex;
        justify-content: space-around;
        margin-top: 20px;
    }
    .content-wrapper > :nth-child(3)
    {
        grid-column: 3;
        grid-row: 1;
    }
</style>
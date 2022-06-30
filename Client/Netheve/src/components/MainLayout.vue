<script setup>
  import Navbar from "./Navbar.vue";
  import BodyContent from "./BodyContent.vue"
</script>

<template>
    <section>
        <div class="body-wrapper">
            <div>GRID 1</div>
            <div>
                <input type="text" name="" id="" placeholder="Feeling Lucky Today?" class="oswald">
            </div>
            <div>GRID 3</div>
        </div>
    </section>
    <BodyContent/>
</template>

<style>
.body-wrapper
{
    display: grid;
    grid-template-columns: 3;
    grid-template-rows: 1;
    margin-top: 20px;
}
.body-wrapper > :nth-child(1){
    grid-column: 1;
    grid-row: 1;
    background-color: transparent;
}
.body-wrapper > :nth-child(2){
    grid-column: 2;
    grid-row: 1;
    background-color: transparent;
}
.body-wrapper > :nth-child(2) > *{
    width: 100%;
    padding: 10px;
    border-radius: 20px;
    border: none;
    outline-color: #083D77;
}
.body-wrapper > :nth-child(2) > *:default{
    outline: none;
}
.body-wrapper > :nth-child(3){
    grid-column: 3;
    grid-row: 1;
    background-color: transparent;
}
.wrapper > * {
    display: none;
}
</style>
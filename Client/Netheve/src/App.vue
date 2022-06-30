<script setup>
  import Navbar from "./components/Navbar.vue";
  import MainLayout from "./components/MainLayout.vue"
</script>

<template>
  <header>

  </header>

  <main>
    <Navbar/>
    <MainLayout/>
  </main>
</template>

<style>
@import "./assets/base.css";

body{
  background-image: url(../public/bg/mainbg.jpg);
}
</style>

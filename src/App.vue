
<script setup>
import Head from './components/Headr.vue'
import FoterMobilka from './components/Memu.vue'
</script>

<template>
<Head />
<img class="Sliders" src=".//assets/Sliders.svg"> 
<div class="qwe"><FoterMobilka/></div>
</template>

<style>
    .Sliders{
        width: 100%;
    }

    @media (max-width: 768px){
    .Sliders {
        width: 100%;
    }
}
@media (min-width: 540px) {
    .qwe{
        display: none;
    }
}
</style>

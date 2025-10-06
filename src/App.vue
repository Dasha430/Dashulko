
<script setup>
import Headr from './components/Headr.vue'
import FoterMobilka from './components/Memu.vue'
import KartochkaTovara from './components/KartochkaTovara.vue';
import Star from './components/Star.vue';
</script>

<template>
    
<Headr />
<img class="Sliders" src=".//assets/Sliders.svg"> 
<KartochkaTovara/>
<div class="FoterMobilka"><FoterMobilka/></div>
</template>

<style>
    .FoterMobilka{
        display: none;
}
    .Sliders{
        width: 100%;
    }

    @media (max-width: 768px){
    .Sliders {
        width: 100%;
    }
}
@media (max-width: 540px) {
    .FoterMobilka{
        display: flex;
}
}
</style>

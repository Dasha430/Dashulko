
<script setup>
import Headr from './components/Headr.vue';
import FoterMobilka from './components/Memu.vue';
import KartochkaTovara from './components/KartochkaTovara.vue';
</script>

<template>
    
<Headr />
<img class="Sliders" src=".//assets/Sliders.svg"> 

<div class="FoterMobilka"><FoterMobilka/></div>
<div class="heading_and_tovar">
    <span><b>Акции</b></span>
    <div class="right">
        <span class="all_sale">Все акции</span>
        <img src=".//assets/chevron_right.svg">
    </div>
    <div class="all_tovar">
        <KartochkaTovara/>
        <KartochkaTovara/>
        <KartochkaTovara/>
    </div>
</div>
</template>

<style>
    .heading_and_tovar{
        font-size: 36px;
        background: #FBF8EC;
        flex-wrap: wrap;
        display: flex;
        text-align: left;
        padding: 0 116px 0 116px;
        color: #414141;
        justify-content: space-between;
    }

    .right{
        padding: 0 0 8px 0;
        color: #606060;
        font-size: 16px;
        padding: 8px;
    }

    .FoterMobilka{
        display: none;
    }
    .Sliders{
        width: 100%;
    }

    .all_tovar{
        width: 100%;
        flex-wrap: wrap;
        display: flex;
        justify-content: center;
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

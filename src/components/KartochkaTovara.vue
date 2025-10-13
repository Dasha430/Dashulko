<script setup>
import Star from './Star.vue';
</script>
<template lang="">

<div class="osn">
    <div class="img">
        <img src="..//assets/blinchki.svg">
    </div>

    <div class="inf">

        <div class="top">
            <div class="left">
                <span class="price"><b>44,50</b></span>
                <span class="light_text">С картой</span>
            </div>

            <div class="right">
                <span class="name_tovara">50,50 ₽</span>
                <span class="light_text">Обычная</span>
            </div>
        </div>

        <div class="botom">
            <p class="name_tovara">Г/Ц Блинчики с мясом вес, Россия</p>
            <Star rate="4"/>
            <button class="korzina">В корзину</button>
        </div>
    </div>
</div>

</template>
<script>
export default {

}
</script>
<style>
* {
    font-family: "Rubik", sans-serif;
    font-optical-sizing: auto;
    font-weight: weight;
    font-style: normal;
}

.inf{
    display: grid;
    gap: 8px;
    padding: 8px;
}

.img{
    width: 100%;
}

.top{
    display: flex;
    justify-content: space-between;
}

.left{
    display: grid;
}

.right{
    display: grid;
}

.osn{
    background: white;
    height: 100%;
    max-width: 272px;
    display: grid;
    justify-content: center;
    border-radius: 4px;
}

.light_text{
    color: #BFBFBF;
    font-size: 12px;
}

.name_tovara{
    font-size: 16px;
    display: flex;
    width: 100%;
    line-height: 16px;
    text-wrap:wrap;
    max-height: 32px;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2; 
}

.price{
    font-size: 18px;
}

.korzina{
    border-radius: 4px;
    background: white;
    border: 1px solid #70C05B;
    color: #70C05B;
    text-align: center;
    font-size: 16PX;
    width: 100%;
    padding: 8px;
}
</style>
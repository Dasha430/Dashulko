<template lang="">

   <div class="foot">
        <div class="fob">
            <div class="img_size">
                <div><img src="..//assets/katalog.svg"></div>
                    <p>Избранное</p> 
           </div> 
           <div class="img_size">
                <div><img src="..//assets/favourites.svg"></div>
                    <p>Избранное</p> 
           </div> 
           <div class="img_size">
                <div><img src="..//assets/orders.svg"></div> 
                <p>Заказы</p> 
           </div> 
           <div class="img_size">
                <div><img src="..//assets/basket.svg"></div>
                <p>Корзина</p> 
           </div> 

           <div class="av_pol">
                <div class="avatar">
                    <img class="av_position" src="..//assets/avatar.svg">
                </div>
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

.foot {
    display: flex;
    align-items: center;
    justify-content: center;
    grid-gap: 40px;
    padding: 16px;
    margin: 0px;
    border-bottom: solid #EAE7DC;
    margin-top: -100px;
}


.kat_ser_logo {
    display: flex;
    gap: 16px;
    width: 100%;
}

.kat_ser {
    display: flex;
    gap: 16px;
    width: 100%;
    justify-content: space-between;
}

.fob {
    display: flex;
    gap: 24px;
}

.img_size {
    align-items: center;
    Text-align: center;
    font-size: 12px;
    color: #414141;
    justify-content: center;
    display: grid;
}

.av_pol {
    display: flex;
    align-items: center;
    justify-content: space-between;
    Text-align: center;
    gap: 10px;
}

.avatar {
    position: relative;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: #cfcfcf;
}

@media (max-width: 540px) {

    .btn_katalog {
        width: 40px;
        height: 40px;
    }

    .arrow {
        display: none;
    }

    .name {
        display: none;
    }

    .kat_text {
        display: none;
    }
    .fob{
        display: none;
    }
}
</style>
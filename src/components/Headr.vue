<template lang="">

   <div class="head">
        <div class="kat_ser_logo">
            <div class="logo">
                <img class="logo_img" src="..//assets/logo.svg"></img>
                <img class="logo_text" src="..//assets/logo_text.svg"></img>
            </div>

            <div class="kat_ser">
                <div class="btn_katalog">
                    <img src="..//assets/menu.svg"></img>
                    <p class="kat_text">Каталог</p>
                </div>

                <div class="search">
                        <p>Найти товар</p>
                        <img src="..//assets/search.svg"> 
                </div>
            </div>
        </div>

        <div class="fob">
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
                <div class="name">Алексей</div>
                <img class="arrow" src="..//assets/chevron_down.svg">
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

.head {
    display: flex;
    align-items: center;
    justify-content: center;
    grid-gap: 40px;
    padding: 16px;
    margin: 0px;
    border-bottom: solid #EAE7DC;
}

.logo {
    display: FLEX;
    width: 152px;
    align-items: center;
    justify-content: center;
    gap: 10px;
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

.btn_katalog {
    background: #70C05B;
    color: #ffffff;
    border-radius: 4px;
    align-items: center;
    justify-content: center;
    Text-align: center;
    display: flex;
    grid-gap: 8px;
    padding: 0 8px;
    font-size: 16px;
    height: 40px;
}

.search {
    width: 100%;
    height: 40px;
    border-radius: 4px;
    border: 1px solid #70C05B;
    color: #8F8F8F;
    font-size: 16px;
    align-items: center;
    justify-content: space-between;
    Text-align: center;
    display: flex;
    padding: 0 8px;
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

.av_position {}

.name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    Text-align: center;
    font-size: 16px;
}

.arrow {
    width: 24px;
    align-items: center;
    justify-content: space-between;
    Text-align: center;
    display: flex;
}

@media (max-width: 900px) {

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
}
@media (max-width: 660px) {
    .logo_text{
        display: none;
    }
    .kat_ser_logo{
        gap: 20px;
    }
    .logo_img{
        width: 47px;
        height: 40px;
    }   
    .logo{
        width: 47px;
        height: 40px;
    }   
}
@media (max-width: 540px) {

    .btn_katalog {
        width: 40px;
        height: 40px;
    }

    .btn_katalog{
        display: none;
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
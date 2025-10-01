<template lang="">

   <div class="head">
        <div class="logo">
            <img src="..//assets/logo.svg"></img>
        </div>
      
        <div class="btn_katalog">
            <img src="..//assets/menu.svg"></img>
            <p>Каталог</p>
        </div>
   </div>

</template>
<script>
export default {
    
}
</script>
<style>
        .head{
            display: flex;
            align-items: center;
            justify-content: left;
            grid-gap: 8px;
            margin:0px;
            border-bottom: solid #EAE7DC;
        
        }
        .btn_katalog{
        background: #70C05B;
        color: #ffffff;
        width: 140px;
        border-radius: 4px;
        align-items: center;
        justify-content: center;
        Text-align: center;
        display: flex;
        grid-gap: 8px;
    }
</style>
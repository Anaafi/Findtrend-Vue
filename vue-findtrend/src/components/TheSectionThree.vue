<script setup>
import CompaniesCard from './CompaniesCard.vue';
import microsoft from '../assets/microsoft.png'
import allianz from '../assets/allianz.png'
import upwork from '../assets/upwork.png'
import volvo from '../assets/volvo.png'
import grab from '../assets/grab.png'
import verizon from '../assets/verizon.png'
import coinbase from '../assets/coinbase.png'
import expedia from '../assets/expedia.png'
import airtable from '../assets/airtable.png'
import magento from '../assets/magento.png'
import carrera from '../assets/carrera.png'
import bonanza from '../assets/bonanza.png'
import wetransfer from '../assets/wetransfer.png'
import suzuki from '../assets/suzuki.png'
import algolia from '../assets/algolia.png'
import heineken from '../assets/heineken.png'
</script>

<template>
<div class="main3">
    <p>Findtrend helps you to increase your productivity and reduce your computer's 
        memory load,<span class="main3-txt">an application that can fulfill your daily browsing needs.</span>
    </p>
    <h2>Findtrend make +1000 Startup grow</h2>
    
    <div class="companies-grid">
        <companies-card class="imgcom" :imageUrl="microsoft"/>
        <companies-card class="imgcom" :imageUrl="allianz"/>
        <companies-card class="imgcom" :imageUrl="upwork"/>
        <companies-card class="imgcom" :imageUrl="volvo"/>
        <companies-card class="imgcom" :imageUrl="grab"/>
        <companies-card class="imgcom" :imageUrl="verizon"/>
        <companies-card class="imgcom" :imageUrl="coinbase"/>
        <companies-card class="imgcom" :imageUrl="expedia"/>
        <companies-card class="imgcom" :imageUrl="airtable"/>
        <companies-card class="imgcom" :imageUrl="magento"/>
        <companies-card class="imgcom" :imageUrl="carrera"/>
        <companies-card class="imgcom" :imageUrl="bonanza"/>
        <companies-card class="imgcom" :imageUrl="wetransfer"/>
        <companies-card class="imgcom" :imageUrl="suzuki"/>
        <companies-card class="imgcom" :imageUrl="algolia"/>
        <companies-card class="imgcom" :imageUrl="heineken"/>
    </div>
    
</div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600;700;800;900&display=swap');
.main3{
    display: flex;
    flex-direction: column;
}
.main3 p{
    color: #000;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: normal;
    padding: 80px 22px 160px 22px;
}
.main3-txt{
    color: #ADADAD;
}

.main3 h2{
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: normal;
    padding: 0px 20px 32px 20px;
}
/*.grid-container{
    display: flex;
    align-items: center;
    justify-content: center;
}*/
.companies-grid{
    display: grid;
    grid-template-rows: repeat(8, 1fr);
    grid-template-columns: 1fr 1fr;
    gap: 15px;
    margin: 0 auto;
    padding-bottom: 80px;
    /*display: flex;
    flex-wrap: wrap;
    width: 50%; 
    box-sizing: border-box;
    gap: 10px;*/
    
    
}

.imgcom{
    display: flex;
    padding: 25px 0px;
    justify-content: center;
    align-items: center;
    width: 167px;
}
@media (min-width: 1024px){
 .main3 p{
    font-weight: 700;
    font-size: 64px;
    padding: 140px 140px 280px 140px;
 }
 .main3 h2{
    font-weight: 700;
    font-size: 64px;
    padding-bottom: 80px;
 }
 .companies-grid{
    display: grid;
    grid-template-rows: repeat(4, 1fr);
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
    padding-bottom: 140px;
    margin: 0 auto;
   /*display: flex;
    flex-wrap: wrap; 
    box-sizing: border-box;
    align-items: center;
    justify-content: center;
    gap: 10px;*/
 }
 .imgcom{
    width: 200px;
    padding: 40px 0px;
 }
}

@media (min-width: 1125px){
    .imgcom{
        width: 266px;
    }
}

</style>

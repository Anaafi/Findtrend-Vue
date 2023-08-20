<script setup>
import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
  <div class="main6">
    <h1>Join us on email for</h1>
    <h2>more trending topics</h2>
    <div class="btn-com">
    <ButtonComponent class="main6-btn" button-text="Join Now"/>
    </div>
  </div>  
</template>

<style scoped>
.main6{
    display: flex;
    flex-direction: column;
    justify-content: center;
    background: #A8FF35;
}
.main6 h1{
    color: #000;
    text-align: center;
    font-family: 'Inter';
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%;
    padding-top: 80px;
}
.main6 h2{
    color: #87D322;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%;
}
.main6-btn{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%; 
    padding: 12px 24px;
    margin: 0 auto;
    background: #000;   

}
.btn-com{
    display: flex;
    justify-content: center;
    padding-top: 40px;
    padding-bottom: 80px;
}
@media (min-width: 1024px){
    .main6 h1{
        font-size: 72px;
        font-weight: 900;
        padding-top: 140px;
    }
    .main6 h2{
        font-size: 72px;
        font-weight: 900;
    }
    .main6-btn{
        font-size: 18px;
        padding: 16px 32px;
    }
    .btn-com{
        padding-top: 40px;
        padding-bottom: 140px;
    }
}
</style>
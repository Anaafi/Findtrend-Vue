<script setup>
 import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
 <diV class="main5">
    <h1>Get your best deal</h1>
    <div class="main5-top">
        <h3>Monthly</h3>
        <img class="main5-mob" src="../assets/grpp.png"/>
        <img class="main5-dek" src="../assets/grpd.png"/>
        <h4>Yearly</h4>
        <img class="main5-dek" src="../assets/grpd2.png"/>
    </div>
    
    <div class="deals">
    <div class="deal-card1">
        <div class="dc1">
            <h2>Personal</h2>
            <p>Special first packet for all</p>
            <hr>
        </div>
        
        <div class="dc1bt">
            <p><span class="sum">$8</span> /month</p>
            <p>&#x2713; Up to 5 page each group</p>
            <p>&#x2713; Up to 10 group page</p>
            <p>&#x2713; 5 Days group page saved</p>
        </div>
        <div class="dbtn">
        <ButtonComponent class="dbtn-txt" button-text="Start Free Trial"/>
        </div>
    </div>
    <div class="deal-card1 two">
        <div class="dc1">
            <h2>Regular</h2>
            <p>Recommended for personal pro</p>
            <hr>
        </div>
        
        <div class="dc1bt ctwo">
            <p><span class="sum">$20</span> /month</p>
            <p>&#x2713; Up to 5 page each group</p>
            <p>&#x2713; Download page up to 20 page</p>
            <p>&#x2713; Up to 10 group page</p>
            <p>&#x2713; 5 Days group page saved</p>
        </div>
        <div class="dbtn">
        <ButtonComponent class="dbtn-txt bt" button-text="Start Free Trial"/>
        </div>
    </div>
    <div class="deal-card1">
        <div class="dc1">
            <h2>Personal</h2>
            <p>Special first packet for all</p>
            <hr>
        </div>
        
        <div class="dc1bt cthree">
            <p><span class="sum">$48</span> /month</p>
            <p>&#x2713; Unlimited group pages</p>
            <p>&#x2713; Unlimited download page</p>
            <p>&#x2713; Unlimited page each group</p>
            <p>&#x2713; Customize sorting group pages</p>
            <p>&#x2713; Customize group page name</p>
            <p>&#x2713; 30 Days group page saved</p>
        </div>
        <div class="dbtn">
        <ButtonComponent class="dbtn-txt" button-text="Start Free Trial"/>
        </div>
    </div>
    
    </div>
 </diV>   
</template>

<style scoped>
.main5{ 
    background: #000;
}
.main5-dek{
    display: none;
}
.main5 h1{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: normal;
    padding-top: 80px;
    padding-bottom: 32px;
}

.main5-top{
    display: flex;
    justify-content: center;
    padding-bottom: 18px;
}
.main5-top h3{
    color: #FFF;
    font-family: "Inter";
    font-size: 18px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    padding-right: 10px;
}
.main5-top h4{
    color: #F5F5F5;
    font-family: "Inter";
    font-size: 18px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
}
.deal-card1{
    border-radius: 15.067px;
    background: #FAFAFA;
}
.dc1{
    display: flex;
    flex-direction: column;
    gap: 15px;
    padding-top: 30px;
    padding-left: 30px;
    padding-right: 30px;
}
.deals{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 24px;
    padding: 0px 18px 80px 18px;
}
.dc1 h2{
    color: #000;
    font-family: "Inter";
    font-size: 32px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%;
}
hr{
    width: 279px;
}

p{
    color: #000;
    font-family: "Inter";
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%;
}

.dc1bt{
    display: flex;
    flex-direction: column;
    gap: 30px;
    padding-top: 32px;
    padding-left: 30px;
    
    padding-bottom: 173px;
}
.sum{
    color: #000;
    font-family: "Inter";
    font-size: 60px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%;
}
.dbtn{
    display: flex;
    justify-content: center;
    padding-bottom: 24px;
}
.dbtn-txt{
    padding: 15px 80px;
    background: #A8FF35;
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 18px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%;
}
.two{
    background: #A8FF35;
}
.bt{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 18px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%; 
    background: #000;
}
.ctwo{
    padding-bottom: 125px;
}
.cthree{
    padding-bottom: 26px;
}

@media (min-width: 1024px){
    .main5-dek{
        display: block;
    } 
    .main5-mob{
        display: none;
    }
    .deals{
        flex-direction: row;
        justify-content: center;
        gap: 10px;
        padding-bottom: 140px;
    }
    .main5 h1{
        font-size: 64px;
        font-weight: 700;
        padding-top: 140px;
        padding-bottom: 40px;
    }
    .main5-top{
        padding-bottom: 40px;
        gap: 10px;
    }
    .main5-top h3{
        font-size: 24px;
        padding: none;
    }
    .main5-top h4{
        font-size: 24px;
    }
}
@media (min-width: 1107px){
    .deals{
        gap: 40px;
    }
}
</style>
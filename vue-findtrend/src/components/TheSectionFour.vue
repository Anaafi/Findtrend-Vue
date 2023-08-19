<script setup>

</script>

<template>
  <section class="main4">
    <h2>All platform connect to Findtrend</h2>
    <div class="main4-img">
        <img class="mob" src="../assets/image95.png"/>
        <img class="mob twitter" src="../assets/image96.png"/>
        <img class="mob" src="../assets/Rectangle6.png"/>
        <img class="mob" src="../assets/image97.png"/>
        <img class="dek" src="../assets/facebook.png"/>
        <img class="dek twitter" src="../assets/twitter.png"/>
        <img class="dek" src="../assets/imageT.png"/>
        <img class="dek" src="../assets/imageR.png"/>
        <img class="dek" src="../assets/image113.png"/>
        <img class="dek" src="../assets/image114.png"/>
        <img class="dek" src="../assets/image115.png"/>
        <img class="dek" src="../assets/image112.png"/>
    </div>
    <div class="tweetmob">
        <img src="../assets/tweet1m.png"/>
        <img src="../assets/tweet2m.png"/>
        <img src="../assets/tweet3m.png"/>
    </div>
    <div class="tweetdek">
        <img src="../assets/tweet1.png"/>
        <img src="../assets/tweet2.png"/>
        <img src="../assets/tweet3.png"/>
    </div>
  </section>  
</template>

<style scoped>
.main4{
    background: #FAFAFA;
}
.main4 h2{
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: normal;
    padding-top: 80px;
    padding-bottom: 32px;
}

.dek{
    display: none;
}
.main4-img{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
    padding-bottom: 32px;
}
.mob{
    border-radius: 8px;
    background: #FFF;
    padding: 16.5px;
    
}
.twitter{
    background: #A8FF35;
}

.tweetdek{
    display: none;
}

.tweetmob{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 16px;
    padding: 0px 18px 32px 18px;
}
@media (min-width: 1024px){
    .mob, .tweetmob {
        display: none;
    }
    .dek{
        display: block;
        border-radius: 8px;
        background: #FFF;
        padding: 20px;
    }
    .twitter{
    background: #A8FF35;
    }
    
    .main4 h2{
        font-weight: 700;
        font-size: 64px;
        padding-top: 140px;
        padding-bottom: 80px;
    }

    .main4-img{
        gap: 24px;
        padding-bottom: 77px;
    }

    .tweetdek{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 40px;
    padding: 0px 320px 80px 320px;
    }

}
</style>
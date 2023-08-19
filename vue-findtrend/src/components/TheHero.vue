<script setup>
import TheSocialCard from './TheSocialCard.vue';
import ButtonComponent from './ButtonComponent.vue'; 
import image1 from "../assets/image96.png";
import image2 from "../assets/image97.png";
import image3 from "../assets/image95.png";
import image4 from "../assets/Rectangle6.png";
</script>

<template>
   <section>
    <h2>Minimize your tabs.</h2>
    <h2>Find the trends!</h2>
    <p>Don’t let your computer memories consumes all of those browser tabs. 
        Findtrend  let you gathers all of your favorite website into one place.
    </p>
    <div class="btn-text">
    <div>
    <ButtonComponent class="button" buttonText="Get Started 🔥"/>
    </div>
    <img class="btn-img" src="../assets/img-hero.png"/>
    </div>
    <diV class="social-cards">
        <div>
        <diV class="ts">
        <TheSocialCard class="scard1" :image="image1" socialText="Cryptopunk - Search"/>
        </diV>
        <div class="tp">
        <TheSocialCard class="scard2"  :image="image2" socialText="Popular Design - Search"/>
        </div>
        </div>
        <div>
        <div class="bs">
        <TheSocialCard class="scard3"  :image="image3" socialText="Product Design - Search"/>
        </div>
        <div class="bp">
        <TheSocialCard class="scard4"  :image="image4" socialText="Elon Musk - Search"/>
        </div>
        </div>
    </diV>
   </section>
</template>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600;700;800;900&display=swap');

  .btn-img{
    display: none;
  }
   section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #000;
    padding-top: 56px;
   }

   section h2{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%;
   }
   section p{
    color: #8B8B8B;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    padding: 16px 44px 32px 45px;
   }

   .button{
    background-color: #A8FF35;
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%;
   }

   .social-cards{
    padding: 50px 0px;
    display: flex;
    flex-direction: column;

   }

   .scard1{
    transform: rotate(-4deg);
    
   }
   .scard2{
    transform: rotate(2deg);
    
   }
   .scard3{
    transform: rotate(-2deg);
   }
   .scard4{
    transform: rotate(4deg);
   }

   @media (min-width: 1024px){
    .button{
        padding: 16px 32px;
    }
    .btn-img{
        display: block;
    }
    section h2{
        font-size: 72px;
    }
    section p{
        font-size: 18px; 
        padding: 24px 387px 40px 387px;
    }
    .btn-text{
        display: flex;
        gap: 5px;
    }
    .social-cards{
        flex-direction: row;
        padding: 100px 0px;
    }
   .scard1, .scard2, .scard3, .scard4{
    font-size: 23.806px;
   }
   .tp{
    padding-left: 100px;
   }
   .ts{
    padding-right: 100px;
   }
   .bp{
    padding-left: 150px;
   }
   .bs{
    padding-right: 100px;
   }
}
</style>
<script setup>
import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
    <div class="navbar">
        <img class="logo-phone" src="../assets/llogo.svg"/>
        <img class="menu-icon" src="../assets/menu.svg"/>
        <div class="desk-navbar">
            <img src="../assets/Logo.svg"/>
            <ul>
                <li>About</li>
                <li>How it work</li>
                <li>Pricing</li>
                <li>Solution</li>
                <li>Features</li>
            </ul>
            <div class="nav-btn">
                <p>Login</p>
                <ButtonComponent buttonText="Register" />
            </div>
        </div>
    </div>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap');

    .desk-navbar{
        display: none;
    }
    .navbar{
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: #000000;
        padding: 24px 18px;
    }

@media (min-width: 1024px) {
    .logo-phone, .menu-icon{
        display: none;
    }

    .navbar{
        display: block;
        padding: 28px 0px;

    }

    .desk-navbar{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    ul{
        display: flex;
        color: #FFF;
        /*text-align: center;*/
        font-family: "Inter";
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        line-height: 100%; /* 18px */
        gap: 40px;
    }
    ul li{
        list-style: none;
    }

    .nav-btn{
        display: flex;
        gap: 40px;
        align-items: center;
    }
    .nav-btn p{
        color: #FFF;
        text-align: center;
        font-family: "Inter";
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        line-height: 100%; /* 18px */
    }
}
</style>

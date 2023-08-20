<script setup>

</script>

<template>
    <footer>
        <img class="flogo" src="../assets/footerLogo.svg" />
        <ul>
            <li>Privacy Policy</li>
            <li>Terms and Conditions</li>
            <li>Contact Us</li>
            <li>Careers</li>
        </ul>
    </footer>
</template>

<style scoped>
footer{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 99px;
    padding-top: 62px;
    padding-bottom: 80px;
    align-items: center;
}

ul{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 40px;
}
ul li{
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 100%;
    list-style: none;
}
@media (min-width: 1024px){
    footer{
        flex-direction: row;
        justify-content: space-between;
        padding: 30px 80px;
        gap: 0px;
    }
    ul{
        flex-direction: row;
        gap: 40px;
    }
}
</style>
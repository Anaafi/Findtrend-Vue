<script setup>
    defineProps(["image", "socialText"]);
</script>

<template>
    <div class="socialCard">
        <img :src="image" />
        <p>{{ socialText }}</p>
        <img src="../assets/Group 1.1.svg" />
    </div>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap');
    .socialCard{
        display: flex;
        background-color: #181818;
        padding: 23px 20px;
        gap: 10px;
        align-items: center;
    }
    .socialCard p{
        
        color: #FFF;
        text-align: center;
        font-family: "Inter";
        font-size: 20.445px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
    }
</style>

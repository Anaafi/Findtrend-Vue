<script setup>
    defineProps(["buttonText"]);
</script>

<template>
    <button>{{ buttonText }}</button>
</template>

<style scoped>
    button {
        padding: 12px 32px;
        border-radius: 40px;
        background: #FFF;
        text-align: center;
        font-family: "Inter";
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        border: none;
    }
    
</style>

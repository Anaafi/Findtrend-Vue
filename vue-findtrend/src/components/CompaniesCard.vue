<script setup>
defineProps(["imageUrl"])
</script>

<template>
    <div class="startup">
        <img :src="imageUrl" />
    </div>
    
</template>

<style scoped>
 .startup{
    border-radius: 8px;
    background: #F5F5F5;
    
 }
</style>
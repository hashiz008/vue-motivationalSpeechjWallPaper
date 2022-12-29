<script setup lang="ts">
const text = "Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away. - Antoine de Sain";
const imgs = "https://recursionist.io/img/different-job.png";
</script>

<template>
    <div class="container">
        <img :src="imgs" class="imgStyle">
        <p class="message">{{ text }}</p>
    </div>
</template>

<style scoped>
.container {
    display:flex;
    text-align: center;
    align-items: center;
    flex-direction:column;
}
.imgStyle {
    width:50rem;
    height:40rem;
}
.message {
    display:flex;
    align-items: center;
    position: absolute;
    color:#2c3e50;
    width:400px;
    top:100px;
}
</style>
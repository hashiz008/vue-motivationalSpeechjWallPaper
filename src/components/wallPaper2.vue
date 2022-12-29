<script setup lang="ts">
const text = "The scientist discovers a new type of material or energy and the engineer discovers a new use for it. - Gordon Lindsay Glegg";
const imgs = "https://cdn.pixabay.com/photo/2018/02/23/04/38/laptop-3174729_1280.jpg";
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
}
</style>
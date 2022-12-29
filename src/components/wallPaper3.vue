<script setup lang="ts">
const text = "Scientists study the world as it is, engineers create the world that never has been. - Theodore von Karman";
const imgs = "https://cdn.pixabay.com/photo/2017/05/10/19/29/robot-2301646_1280.jpg";
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
    justify-content:flex-end;
    position: absolute;
    color:#2c3e50;
    width:300px;
}
</style>
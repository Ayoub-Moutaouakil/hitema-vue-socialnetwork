<template>
    <div id="netline">
        <Card v-for="article in articles" :key="article.id" :data="article"></Card>
    </div>
</template>

<script setup>
import { onBeforeMount } from "vue";
import Card from "../components/Card.vue"

    const articles = await fetch(`http://localhost:3000/articles`).then((r) => r.json())
</script>

<style scoped>
#netline {
    width: 95%;
    height: auto;
    margin-top: 30px;
    margin-bottom: 10px;
    /*border-radius: 10px;*/
    overflow-y: scroll;
    overflow-x: hidden;
}
</style>
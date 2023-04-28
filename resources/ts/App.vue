<template>
<div>
    <h1>{{count}}</h1>
</div>
</template>

<script setup lang="ts">
import {ref, onMounted} from "vue";

const count = ref<string>("Hello world");

onMounted(() => {
    console.log('Hello TS VUE VITE LARAVEL')
})
</script>

<style scoped>

</style>

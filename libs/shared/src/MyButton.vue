<template>
    <button class="my_button" @click="increment">My button{{ count }}</button>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const count = ref < number > (0)

const increment = () => {
    count.value += 1
}
</script>

<style scoped>
.my_button {
    background-color: red;
    border-radius: 10px;
    border: 0;
    padding: 10px;
}
</style>
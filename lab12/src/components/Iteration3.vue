<template>
    <div>
        <button @click="">Click</button>
        <p v-if="positive">true</p>
        <p v-else-if="positive">false</p>
    </div>
</template>
<script setup>

import {ref} from'vue';
const positive = ref(true);
const toggle = () => {
    positivo.value = !positive.value
}
</script>

<style scoped>
</style>
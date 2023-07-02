<template>
    <div class="prose">
        <h1>Hey World</h1>
    </div>
</template>

<script setup>
import { onMounted } from 'vue';

onMounted(() => {
    console.log('Dashboard mounted')
})
</script>
<template>
    <div class="grid grid-cols-3 max-h-screen ">
        <div v-for="name in names" :key="index" class="outline">
            {{ name }}
        </div>
    </div>
</template>

<script setup>
import { ref } from 'vue'
const names = ref([
    "Kigembe",
    "Mamba",
    "Muganza",
    "Mugombwa",
    "Mukindo",
    "Mwendo",
])
</script>
<template>
    <div>
        <h1>recipes page</h1>
        <h1>Recipes: {{counterStore.count}}</h1>
        <h1>Recipes: {{counterStore.doubleCount}}</h1>
    </div>
</template>
<script setup>
import { useCounterStore } from '@/stores/counter'
const counterStore = useCounterStore()

</script>

<template>
    <div>
        <h1>dashboard page</h1>
        <h1>{{counterStore.count}}</h1>
        <h1>{{counterStore.doubleCount}}</h1>
        <button @click="counterStore.increment" type="button" class="btn btn-warning btn-sm">Artır</button>
    </div>
</template>
<script setup>
import { useCounterStore } from '@/stores/counter'
const counterStore = useCounterStore()

</script>

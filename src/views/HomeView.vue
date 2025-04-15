<script setup>
// Composition API
import { useProductStore } from '@/stores/product';
import { useCounterStore } from '@/stores/counter';

const counter = useCounterStore()
const product = useProductStore()

</script>

<template>
  <main>
  <h3>This is Home Page</h3>
  </main>
</template>

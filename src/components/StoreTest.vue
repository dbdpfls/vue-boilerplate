<template>
  <div class="count-box">
    <h1>count: {{ counter.count }}</h1>
    <div class="button-box">
      <button @click="counter.increment">increment</button>
      <button @click="counter.decrement">decrement</button>
      <button @click="counter.clear">clear</button>
    </div>
  </div>
</template>

<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'
const counter = useCounterStore()
</script>

<style scoped>
.count-box {
  gap: 10px;
  display: flex;
  flex-direction: column;
  padding: 20px 0;
}

h1 {
  text-align: center;
  color: #00bd7e;
  font-weight: 700;
}

.button-box {
  gap: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
}

button {
  background-color: #00bd7e;
  padding: 5px;
  border: 1px solid #000;
  border-radius: 3px;
  font-size: 15px;
  color: #fff;
}

button:hover {
  background-color: #05db77;
}
</style>

<template>
  <button class="btn" :class="{ 'btn--clicked': wasClicked }" @click="onClick">
    {{ label }}
  </button>
</template>

<script setup>
import { ref } from "vue";

defineProps({
  label: String,
});

const wasClicked = ref(false);

function onClick() {
  wasClicked.value = true;
}
</script>

<style scoped>
.btn {
  background-color: #c1d3ed;
  color: #0675bb;
  border: 2px solid #0675bb;
  padding: 10px;
  margin: 10px;
  border-radius: 20px;
}
.btn--clicked {
  background-color: #0675bb;
  color: #c1d3ed;
  border: 2px solid #c1d3ed;
}
</style>

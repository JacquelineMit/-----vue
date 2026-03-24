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
  background-color: #f0ffff;
  color: #008080;
  border: 2px solid #008080;
  padding: 10px;
  margin: 10px;
  border-radius: 20px;
}
.btn--clicked {
  background-color: #008080;
  color: #f0ffff;
  border: 2px solid #f0ffff;
}
</style>

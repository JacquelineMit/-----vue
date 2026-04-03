<template>
  <div>It is the 13's product</div>
</template>

<script setup>
const route = useRoute();
const id = route.params.id;

console.log("Product ID is", id);
</script>

<template>
  <div class="card">
    <div class="card__content">
      <NuxtLink to="/product/13">
        <img :src="img" :alt="imgAlt" class="img" width="200px" />
      </NuxtLink>
      <p class="title">{{ title }}</p>
      <p>{{ description }}</p>
    </div>
    <Button label="Добавить в корзину"></Button>
  </div>
</template>

<script setup>
defineProps({
  id: [String, Number],
  title: String,
  description: String,
  img: String,
  imgAlt: String,
});
</script>

<style scoped>
.card {
  display: flex;
  padding: 8px;
  flex-direction: column;
  gap: 8px;
}

.card__content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.img {
  border: 2px solid #008080;
  margin: 10px;
}

.title {
  color: #f0ffff;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  font-size: 20px;
  font-weight: bold;
}
</style>

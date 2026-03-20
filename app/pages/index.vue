<template>
  <main class="main">
    <div>
      <div class="card">
        <img
          src="~/assets/img/потребкорзина.jpg"
          alt="собранная корзина"
          class="img"
        />
        <Button label="Добавить в корзину"></Button>
      </div>
      <div>
        <img src="~/assets/img/milk.jpg" alt="молоко" class="img" />
        <Button label="Добавить в корзину"></Button>
      </div>
    </div>
  </main>
</template>

<script setup></script>

<style scoped>
.main {
  background-color: #c1d3ed;
}

.img {
  border: 2px solid #0675bb;
  margin: 10px;
}

.card {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
</style>

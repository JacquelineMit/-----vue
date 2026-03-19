<template>
  <div>
    <img
      src=".картинки\потребкорзина.jpg"
      alt="собранная корзина"
      class="img"
    />
    <img src=".картинки\молоко.jpg" alt="молоко" class="img" />
  </div>
  <div>
    <button class="btn">Добавить в корзину</button>
    <button class="btn">Добавить в корзину</button>
    <button class="btn">Добавить в корзину</button>
  </div>
</template>

<script></script>

<style>
.btn {
  background-color: aliceblue;
  color: brown;
  border: 2px solid brown;
  padding: 10px;
  margin: 10px;
  border-radius: 20px;
}
.btn::after {
  background-color: brown;
  color: aliceblue;
  border: 2px solid aliceblue;
}

.img {
  border: 2px solid brown;
  margin: 10px;
}
</style>

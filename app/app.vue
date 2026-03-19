<template>
  <body class="main">
    <header class="header">
      <div>
        <button class="btn">Назад</button>
      </div>
    </header>
    <main>
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
      </div>
    </main>
  </body>
</template>

<script></script>

<style>
.main {
  background-color: #c1d3ed;
}

.header {
  background-color: #0675bb;
}

.btn {
  background-color: #c1d3ed;
  color: #0675bb;
  border: 2px solid #0675bb;
  padding: 10px;
  margin: 10px;
  border-radius: 20px;
}
.btn::after {
  background-color: #0675bb;
  color: #c1d3ed;
  border: 2px solid #c1d3ed;
}

.img {
  border: 2px solid #0675bb;
  margin: 10px;
}
</style>

<template>
  <main class="main">
    <div class="cards-container">
      <ProductCard
        :img="import('~/assets/img/korzina.jpg')"
        imgAlt="Корзина продуктов"
        title="Корзина продуктов"
        description="Собраны базовые продукты для жизнедеятельности"
      ></ProductCard>
      <div class="card">
        <img
          src="~/assets/img/milk.jpg"
          width="200px"
          alt="молоко"
          class="img"
        />
        <p class="text">Молоко</p>
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img src="~/assets/img/hleb.jpg" width="200px" alt="Хлеб" class="img" />
        <p class="text">Хлеб</p>
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/makarons.jpg"
          width="200px"
          alt="Пачка макарон"
          class="img"
        />
        <p class="text">Пачка макарон</p>
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/grehca.jpg"
          width="200px"
          alt="Упаковка гречки"
          class="img"
        />
        <p class="text">Упаковка гречки</p>
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/maso.jpg"
          width="200px"
          alt="Стейк говядины"
          class="img"
        />
        <p class="text">Стейк говядины</p>
        <Button label="Добавить в корзину"></Button>
      </div>
    </div>
  </main>
  <Footer></Footer>
</template>

<script setup></script>

<style scoped>
.main {
  background-color: #20b2aa;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  overflow-x: hidden;
}

.cards-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}
</style>

<template>
  <main class="main">
    <div class="cards-container">
      <div class="card">
        <div class="card__content">
          <NuxtLink to="/about">
            <a href="../app/polnoefoto.vue">
              <img
                src="~/assets/img/korzina.jpg"
                alt="собранная корзина"
                class="img"
                width="200px"
              />
            </a>
          </NuxtLink>
          <p class="text">Корзина продуктов</p>
        </div>
        <Button label="Добавить в корзину"></Button>
      </div>
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

.img {
  border: 2px solid #008080;
  margin: 10px;
}

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

.cards-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}

.text {
  color: #f0ffff;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  font-size: 20px;
  font-weight: bold;
}
</style>

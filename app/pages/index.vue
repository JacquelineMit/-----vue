<template>
  <main class="main">
    <div>
      <div class="card">
        <a href="..app/polnoefoto.vue/korzina.vue">
          <img
            src="~/assets/img/korzina.jpg"
            alt="собранная корзина"
            class="img"
            width="200px"
          />
        </a>
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/milk.jpg"
          width="200px"
          alt="молоко"
          class="img"
        />
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/hleb.jpg"
          width="200px"
          alt="молоко"
          class="img"
        />
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/makarons.jpg"
          width="200px"
          alt="молоко"
          class="img"
        />
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/grehca.jpg"
          width="200px"
          alt="молоко"
          class="img"
        />
        <Button label="Добавить в корзину"></Button>
      </div>
      <div class="card">
        <img
          src="~/assets/img/maso.jpg"
          width="200px"
          alt="молоко"
          class="img"
        />
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

<template>
  <Header>
    <a href="~/pages/index.vue">
      <Button></Button>
    </a>
  </Header>
  <p class="text">Корзина продуктов</p>
  <form class="form">
    <div class="flex-container">
      <img
        src="~/assets/img/korzina.jpg"
        class="fotos"
        width="500px"
        alt="Фото корзины"
      />
    </div>
  </form>
  <Footer></Footer>
</template>

<style>
.fotos {
  border: medium solid;
  border-color: #008080;
}
</style>

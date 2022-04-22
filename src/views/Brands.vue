<template>
  <section id="brands">
    <header class="brands-heading">
      <h2 class="display-2 lead text-center text-black">
        Our <strong>Brands.</strong>
      </h2>
      <p class="display-5 text-center text-black">
        Apparel companies we work with and stock.
      </p>
    </header>
    <main class="brands-grid">
      <div class="brands-item shadow-sm">
        <img src="../images/brands/adidas.png" />
      </div>
      <div class="brands-item shadow-sm">
        <img src="../images/brands/converse.png" />
      </div>
      <div class="brands-item shadow-sm">
        <img src="../images/brands/jordan.png" />
      </div>
      <div class="brands-item shadow-sm">
        <img src="../images/brands/new-balance.png" />
      </div>
      <div class="brands-item shadow-sm">
        <img src="../images/brands/nike.png" />
      </div>
      <div class="brands-item shadow-sm">
        <img src="../images/brands/puma.png" />
      </div>
      <div class="brands-item shadow-sm">
        <img src="../images/brands/timberland.png" />
      </div>
      <div class="brands-item shadow-sm">
        <img src="../images/brands/under-armour.png" />
      </div>
    </main>
  </section>
</template>

<script>
export default {
  name: "Brands",
};
</script>

<style scoped>
section {
  margin-top: 2.5rem;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-height: 100vh;
  flex-direction: column;
  gap: 2rem;
}
header {
  width: 80%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.brands-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(25%, auto);
  width: 80%;
  gap: 1rem;
}
.brands-item {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: 250px;
}
img {
  width: 150px;
  height: auto;
}
@media screen and (max-width: 768px) {
  .brands-grid {
    width: 95%;
    grid-template-columns: 1fr;
    grid-auto-rows: auto;
  }
  header {
    width: 95%;
  }
}
</style>

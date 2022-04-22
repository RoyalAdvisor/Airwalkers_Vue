<template>
  <section id="about">
    <header class="about-heading">
      <h2 class="display-2 lead text-center text-black">
        Who We <strong>Are.</strong>
      </h2>
      <p class="display-5 text-center text-black">
        Airwalkers started at as small, garage-based startup, driven to deliver
        quality footwear since 1997.
      </p>
    </header>
    <main class="image-grid">
      <img src="../images/shoes/shoe1-min.jpg" />
      <img src="../images/shoes/shoe2-min.jpg" />
      <img src="../images/shoes/shoe3-min.jpg" />
      <img src="../images/shoes/shoe4-min.jpg" />
      <img src="../images/shoes/shoe5-min.jpg" />
      <img src="../images/shoes/shoe6-min.jpg" />
    </main>
  </section>
</template>
<script>
export default {
  name: "AboutView",
};
</script>

<style scoped>
section {
  margin-top: 5rem;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  /* min-height: 100vh; */
  flex-direction: column;
  gap: 2rem;
}
header {
  width: 80%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.image-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-auto-rows: minmax(30%, auto);
  width: 80%;
  gap: 1rem;
}
img {
  justify-self: stretch;
  align-self: stretch;
  width: 100%;
  object-fit: cover;
}
@media screen and (max-width: 768px) {
  .image-grid {
    grid-template-columns: 1fr;
    grid-auto-rows: auto;
    width: 95%;
  }
  header {
    width: 95%;
  }
}
</style>

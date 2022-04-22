<template>
  <section id="services">
    <header class="services-heading">
      <h2 class="display-2 lead text-center text-black">
        What We <strong>Do.</strong>
      </h2>
      <p class="display-5 text-center text-black">
        We ensure we import only the latest, freshest, cleanest sneakers and
        offer it at the most affordable prices
      </p>
    </header>
    <main class="services-grid">
      <div class="services-item shadow-sm">
        <div class="services-icon">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="bi bi-coin"
            viewBox="0 0 16 16"
          >
            <path
              d="M5.5 9.511c.076.954.83 1.697 2.182 1.785V12h.6v-.709c1.4-.098 2.218-.846 2.218-1.932 0-.987-.626-1.496-1.745-1.76l-.473-.112V5.57c.6.068.982.396 1.074.85h1.052c-.076-.919-.864-1.638-2.126-1.716V4h-.6v.719c-1.195.117-2.01.836-2.01 1.853 0 .9.606 1.472 1.613 1.707l.397.098v2.034c-.615-.093-1.022-.43-1.114-.9H5.5zm2.177-2.166c-.59-.137-.91-.416-.91-.836 0-.47.345-.822.915-.925v1.76h-.005zm.692 1.193c.717.166 1.048.435 1.048.91 0 .542-.412.914-1.135.982V8.518l.087.02z"
            />
            <path
              d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
            />
            <path
              d="M8 13.5a5.5 5.5 0 1 1 0-11 5.5 5.5 0 0 1 0 11zm0 .5A6 6 0 1 0 8 2a6 6 0 0 0 0 12z"
            />
          </svg>
        </div>
        <div class="services-content">
          <h2 class="display-6 text-center text-black">Exceptional Value</h2>
        </div>
      </div>
      <div class="services-item shadow-sm">
        <div class="services-icon">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="bi bi-lightning"
            viewBox="0 0 16 16"
          >
            <path
              d="M5.52.359A.5.5 0 0 1 6 0h4a.5.5 0 0 1 .474.658L8.694 6H12.5a.5.5 0 0 1 .395.807l-7 9a.5.5 0 0 1-.873-.454L6.823 9.5H3.5a.5.5 0 0 1-.48-.641l2.5-8.5zM6.374 1 4.168 8.5H7.5a.5.5 0 0 1 .478.647L6.78 13.04 11.478 7H8a.5.5 0 0 1-.474-.658L9.306 1H6.374z"
            />
          </svg>
        </div>
        <div class="services-content">
          <h2 class="display-6 text-center text-black">Fast Delivery</h2>
        </div>
      </div>
      <div class="services-item shadow-sm">
        <div class="services-icon">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="bi bi-check2-circle"
            viewBox="0 0 16 16"
          >
            <path
              d="M2.5 8a5.5 5.5 0 0 1 8.25-4.764.5.5 0 0 0 .5-.866A6.5 6.5 0 1 0 14.5 8a.5.5 0 0 0-1 0 5.5 5.5 0 1 1-11 0z"
            />
            <path
              d="M15.354 3.354a.5.5 0 0 0-.708-.708L8 9.293 5.354 6.646a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l7-7z"
            />
          </svg>
        </div>
        <div class="services-content">
          <h2 class="display-6 text-center text-black">Quality Assurance</h2>
        </div>
      </div>
    </main>
  </section>
</template>

<script>
export default {
  name: "Services",
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
main {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-auto-rows: auto;
  width: 80%;
  gap: 1rem;
}
main > div {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: 400px;
  gap: 2rem;
}
.services-icon > svg {
  width: 100px;
  height: auto;
  color: black;
}

@media screen and (max-width: 768px) {
  main {
    grid-template-columns: 1fr;
    width: 95%;
  }
  header {
    width: 95%;
  }
}
</style>

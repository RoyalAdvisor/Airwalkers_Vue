<template>
  <nav class="navbar navbar-light bg-white static-top p-2">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">AIRWALKERS</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="offcanvas"
        data-bs-target="#offcanvasNavbar"
        aria-controls="offcanvasNavbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="offcanvas offcanvas-end"
        tabindex="-1"
        id="offcanvasNavbar"
        aria-labelledby="offcanvasNavbarLabel"
      >
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">AIRWALKERS.</h5>
          <button
            type="button"
            class="btn-close text-reset"
            data-bs-dismiss="offcanvas"
            aria-label="Close"
          ></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home"
                >Home</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#about"
                >About</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#services"
                >Services</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link active"
                aria-current="page"
                href="#testimonials"
                >Testimonials</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#brands"
                >Brands</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#contact"
                >Contact</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.navbar {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 5;
}
</style>

<template>
  <section id="home">
    <div class="home-heading">
      <h2 class="display-2 lead text-center text-black">
        Welcome to <strong>AIRWALKERS.</strong>
      </h2>
    </div>
    <div class="carousel-container">
      <div
        id="carouselExampleDark"
        class="carousel slide"
        data-bs-ride="carousel"
      >
        <div class="carousel-indicators">
          <button
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide-to="0"
            class="active"
            aria-current="true"
            aria-label="Slide 1"
          ></button>
          <button
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide-to="1"
            aria-label="Slide 2"
          ></button>
          <button
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide-to="2"
            aria-label="Slide 3"
          ></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="2000">
            <div class="carousel-image-1">
              <div class="overlay">
                <div class="carousel-caption d-md-block display-6 text-white">
                  <h5 class="display-4">Latest Drops</h5>
                  <p>All the hottest kicks on the block!</p>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item" data-bs-interval="2000">
            <div class="carousel-image-2">
              <div class="overlay">
                <div class="carousel-caption d-md-block display-6 text-white">
                  <h5 class="display-4">Freshest Kicks</h5>
                  <p>Great deals on all sneakers!</p>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item" data-bs-interval="2000">
            <div class="carousel-image-3">
              <div class="overlay">
                <div class="carousel-caption d-md-block display-6 text-white">
                  <h5 class="display-4">Elevate your Style</h5>
                  <p>Take your street cred to the next level!</p>
                </div>
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Featured",
};
</script>
<style scoped>
section {
  margin-top: 2.5rem;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.home-heading {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 40px;
}
.carousel-container {
  width: 100%;
  border-radius: none;
  min-height: 70vh;
}
.carousel-inner {
  min-height: 100%;
}
.overlay {
  width: 100%;
  height: 70vh;
  background-color: rgba(0, 0, 0, 60%);
}
@media screen and (max-width: 768px) {
  .carousel-caption {
    min-height: 100%;
  }
}
.carousel-caption {
  height: 45vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.carousel-image-1 {
  width: 100%;
  height: 70vh;
  background-image: url("../images/landing1-min.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.carousel-image-2 {
  width: 100%;
  height: 70vh;
  background-image: url("../images/landing2-min.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.carousel-image-3 {
  width: 100%;
  height: 70vh;
  background-image: url("../images/landing3-min.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.carousel-item h5,
p {
  color: #fff;
}
h5 {
  font-weight: 400;
}
</style>

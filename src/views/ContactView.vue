<template>
  <section id="contact">
    <header class="contact-heading">
      <h2 class="display-2 lead text-center text-black">
        Get In <strong>Touch.</strong>
      </h2>
      <p class="display-5 text-center text-black">
        Got something on your mind? Fill out the form below and we'll get back
        to you.
      </p>
    </header>
    <div class="overlay">
      <main>
        <Form />
        <Footer />
      </main>
    </div>
  </section>
</template>

<script>
import Form from "@/components/Form.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "ContactView",
  components: {
    Form,
    Footer,
  },
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
.overlay {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  background: url("../images/shoes/landscape2-min.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
main {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  background: rgba(0, 0, 0, 60%);
}
</style>

<template>
  <Navbar />
  <Featured />
  <AboutView />
  <Services />
  <Testimonials />
  <Brands />
  <ContactView />
</template>
<script>
import Navbar from "@/components/Navbar.vue";
import Featured from "@/views/Featured.vue";
import AboutView from "@/views/AboutView.vue";
import Services from "@/views/Services.vue";
import Testimonials from "@/views/Testimonials.vue";
import Brands from "@/views/Brands.vue";
import ContactView from "@/views/ContactView.vue";
export default {
  components: {
    Navbar,
    Featured,
    AboutView,
    Services,
    Testimonials,
    Brands,
    ContactView,
  },
};
</script>
<style>
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>

<template>
  <div id="app">
    <!-- <Nav /> -->
    <section class="parallax-container">
      <Header />
    </section>
    <section class="buffer"></section>
    <section class="parallax-container-2">
      <Author />
      <Book />
      <Buy />
    </section>
    <section class="buffer"></section>
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Nav from "./components/Nav.vue";
import Author from "./components/Author.vue";
import Book from "./components/Book.vue";
import Buy from "./components/Buy.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    Header,
    Nav,
    Author,
    Book,
    Buy,
    Contact,
    Footer,
  },
};
</script>



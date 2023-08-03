<template>
  <div id="app">
    <section class="parallax-container">
      <Header />
    </section>
    <section class="buffer"></section>
    <section class="parallax-container-2">
      <Author />
      <Book />
      <Buy />
      <Contact />
    </section>
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Author from "./components/Author.vue";
import Book from "./components/Book.vue";
import Buy from "./components/Buy.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    Header,
    Author,
    Book,
    Buy,
    Contact,
    Footer,
  },
};
</script>



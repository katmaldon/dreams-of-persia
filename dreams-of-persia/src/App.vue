<template>
  <div id="app">
    <nav class="nav"></nav>

    <Nav>
      <ul class="topnav">
        <li><a class="nav__link" href="#home">Home</a></li>
        <li><a class="nav__link" href="#about">About Us</a></li>
        <li><a class="nav__link" href="#contact">Contact</a></li>
      </ul>
    </Nav>

    <Header />
    <Author />
    <Book />
    <Buy />
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



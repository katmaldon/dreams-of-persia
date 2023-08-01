<template>
  <div id="app">
    <nav class="main-nav"></nav>

    <Nav>
      <ul class="topnav">
        <li><a class="nav__link" href="#home">Home</a></li>
        <li><a class="nav__link" href="#about">About Us</a></li>
        <li><a class="nav__link" href="#contact">Contact</a></li>
      </ul>
    </Nav>

    <Header />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Nav from "./components/Nav.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    Header,
    Nav,
    Footer,
  },
};
</script>



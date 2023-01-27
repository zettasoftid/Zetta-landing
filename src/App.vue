<template>
  <div id="App">
    <Navbar />
    <Header />
    <Section />
    <Content />
    <Contact />
    <Sosmed />
    <Footer />
  </div>
</template>

<script>
  import Navbar from "./components/Navbar.vue";
  import Header from "./components/Header.vue";
  import Section from "./components/Section.vue";
  import Content from "./components/Content.vue";
  import Contact from "./components/Contact.vue";
  import Sosmed from "./components/Sosmed.vue";
  import Footer from "./components/Footer.vue";

  export default {
    name: "App",
    components: {
      Navbar,
      Header,
      Section,
      Content,
      Contact,
      Sosmed,
      Footer,
    },
  };
</script>

<style></style>

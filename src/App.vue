<template>
  <div id="app">
    <Header />
    <div class="container">
      <videotab />
      <Courses />
      <Reviews />
    </div>
    <Footer />
  </div>
</template>

<style>
@import "./style.css";
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css");
</style>

<script>
import Header from "./components/Header";
import videotab from "./components/videotab";
import Courses from "./components/Courses";
import Reviews from "./components/Reviews";
import Footer from './components/Footer';

export default {
  name: "App",
  components: {
    Header,
    videotab,
    Courses,
    Reviews,
    Footer
  },
};
</script>

<template>
  <div id="app">
    <Header />
    <videotab />
  </div>
</template>

<style>
@import "./style.css";
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css");
</style>

<script>
import Header from "./components/Header";
import videotab from "./components/videotab";

export default {
  name: "App",
  components: {
    Header,
    videotab,
  },
};
</script>

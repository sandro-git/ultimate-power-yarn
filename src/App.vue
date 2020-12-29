<template>
  <Header></Header>
  <img
    src="../src\assets\images\image_principale.webp"
    alt="image de la salle"
  />
  <Maintext></Maintext>
</template>

<script>
import Header from "./components/Header.vue";
import Maintext from "./components/Maintext.vue";

export default {
  name: "App",
  components: {
    Header,
    Maintext
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #182d53;
}
body {
  margin: 0;
}

img {
  width: 100%;
}
</style>

<template>
  <Header class="header"></Header>
  <div class="mainImage"></div>
  <Maintext></Maintext>
  <TexteImage></TexteImage>
  <h1>Nos domaines d'activité : trouvez ce qui vous correspond !</h1>
  <TexteImage></TexteImage>
  <TexteImage></TexteImage>
</template>

<script>
import Header from "./components/Header.vue";
import Maintext from "./components/Maintext.vue";
import TexteImage from "./components/TexteImage.vue";

export default {
  name: "App",
  components: {
    Header,
    Maintext,
    TexteImage
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

.mainImage {
  width: 100%;
  min-height: 560px;
  background-image: url("../src/assets/images/image_principale.webp");
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

h1 {
  text-align: center;
  font-size: 35px;
  color: white;
}
</style>

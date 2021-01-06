<template>
  <Header class="header"></Header>
  <div class="mainImage"></div>
  <Maintext></Maintext>
  <TexteImage
    :text="image1.text"
    :title="image1.title"
    :image="image1.image"
  ></TexteImage>
  <h1>Nos domaines d'activité : trouvez ce qui vous correspond !</h1>
  <TexteImage
    :text="image2.text"
    :title="image2.title"
    :image="image2.image"
  ></TexteImage>
  <TexteImage
    :text="image3.text"
    :title="image3.title"
    :image="image3.image"
  ></TexteImage>
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
  },
  data() {
    return {
      image1: {
        title: "À propos de La Salle",
        text:
          "Coaching personnalisé / Accès libre musculation / Powerlifting / Cross-training / Small group training / Cardio Chez Ultimate Power, le maître-mot est la qualité : vous retrouverez des équipements haut de gamme absolument uniques au département. Les coachs enrichissent activement la vie de nos membres et créent une atmosphère à la fois familiale et performante. Notre objectif sera votre accomplissement !",
        image: "image1.webp"
      },
      image2: {
        title: "À propos de La Salle",
        text:
          "Coaching personnalisé / Accès libre musculation / Powerlifting / Cross-training / Small group training / Cardio Chez Ultimate Power, le maître-mot est la qualité : vous retrouverez des équipements haut de gamme absolument uniques au département. Les coachs enrichissent activement la vie de nos membres et créent une atmosphère à la fois familiale et performante. Notre objectif sera votre accomplissement !",
        image: "image2.webp"
      },
      image3: {
        title: "À propos de La Salle",
        text:
          "Coaching personnalisé / Accès libre musculation / Powerlifting / Cross-training / Small group training / Cardio Chez Ultimate Power, le maître-mot est la qualité : vous retrouverez des équipements haut de gamme absolument uniques au département. Les coachs enrichissent activement la vie de nos membres et créent une atmosphère à la fois familiale et performante. Notre objectif sera votre accomplissement !",
        image: "image3.webp"
      }
    };
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

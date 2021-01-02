<template>
  <div class="wrapper">
    <div class="texte">
      <h2>À propos de La Salle</h2>
      <p>
        Coaching personnalisé / Accès libre musculation / Powerlifting /
        Cross-training / Small group training / Cardio Chez Ultimate Power, le
        maître-mot est la qualité : vous retrouverez des équipements haut de
        gamme absolument uniques au département. Les coachs enrichissent
        activement la vie de nos membres et créent une atmosphère à la fois
        familiale et performante. Notre objectif sera votre accomplissement !
      </p>
    </div>
    <img src="@/assets/images/image1.webp" alt="image de la salle" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.wrapper {
  display: flex;
  width: 90%;
  margin: auto;
}

.wrapper :first-child {
  width: 50%;
}
.texte {
  color: white;
  padding: 25px;
  text-align: center;
  background-color: #f03855;
  font-size: 18px;
}
h2 {
  margin: auto;
  font-size: 40px;
}
img {
  width: 50%;
  height: 490px;
}
</style>

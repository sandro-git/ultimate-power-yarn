<template>
  <div class="wrapper">
    <div class="texte">
      <h2>{{ title }}</h2>
      <p>
        {{ text }}
      </p>
    </div>
    <img :src="image" alt="image de la salle" />
  </div>
</template>

<script>
export default {
  name: "TexteImage",
  props: {
    text: {
      type: String,
      default: ""
    },
    title: {
      type: String,
      default: ""
    },
    image: {
      type: String,
      default: ""
    }
  }
};
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

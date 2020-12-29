<template>
  <header>
    <div class="price">A partir de 40€ par mois !</div>
    <div class="logo">
      <img src="@/assets/images/logo.webp" alt="logo" />
    </div>
    <div class="contact">
      contact@ultimate-power.fr
    </div>
    <div class="icons">
      <img src="@/assets/images/Instagram.webp" alt="instagram logo" />
      <img src="@\assets\images\GooglePlaces.webp" alt="google place" />
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-left: auto;
  margin-right: auto;
  width: calc(100% - 60px - 60px);
}
.price {
  background-color: #f03255;
  margin: 30px 0;
  font-size: 25px;
  padding: 20px;
}

.contact {
  color: white;
}
</style>

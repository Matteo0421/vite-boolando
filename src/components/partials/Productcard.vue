<script>
export default {
  props: {
    productImage: String,
    secondaryImage: String,
    brand: String,
    productName: String,
    price: String,
    oldPrice: String
  }
}
</script>

<template>
  <div class="col">
    <!-- CARD  -->
    <div class="card">
      <div class="card-images">
        <img :src="productImage" alt="1">
        <img class="secondary-image" :src="secondaryImage" alt="1">
        <div class="favourite">
          <i class="fa-solid fa-heart"></i>
        </div>
        <div class="badges">
          <span class="badge discount">-50%</span>
          <span class="badge tag">Sostenibilità</span>
        </div>
      </div>
      
      <div class="card-text">
        <div class="brand">{{ brand }}</div>
        <div class="product-name">{{ productName }}</div>
        <div class="price">
          <span>{{ price }} &euro;</span>
          <del>{{ oldPrice }} &euro;</del>
        </div>
      </div>
    </div>
    <!-- /CARD  -->
  </div>
</template>



<style lang="scss" scoped>
.card {
  margin-bottom: 20px;
}
/* Aggiungi altri stili qui se necessario */
</style>

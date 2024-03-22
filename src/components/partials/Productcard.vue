<script>
  export default {
    props:{

      productImage: String,
      productPrice: String,
    }
  }
</script>

<template>
  <div class="col ">
            
            <!-- CARD  -->
            <div class="card">
              
              <div class="card-images">
                <img :src="productImage" alt="1">
                <img class="secondary-image" src="../../assets/img/1b.webp" alt="1">
                <div class="favourite">
                  <i class="fa-solid fa-heart"></i>
                </div>
                <div class="badges">
                  <span class="badge discount">-50%</span>
                  <span class="badge tag">sostenibilità</span>
                </div>
              </div>
              
              <div class="card-text">
                <div class="brand">Levi's</div>
                <div class="product-name">RELAXED fit tee UNISEX</div>
                <div class="price">
                  <span>14,99 &euro;</span>
                  <del>29,99 &euro;</del>
                </div>
              </div>
            </div>
            <!-- /CARD  -->
            
          </div>

</template>


<style lang="scss" scoped>


.card {
  margin-bottom: 20px;
}.card-images{
  position: relative;
  cursor: pointer;
}.secondary-image{
  display: none;
  position: absolute;
  top:0;
  left: 0;
}.favourite{
  position: absolute;
  background-color: white;
  top: 20px;
  right: 0;
  padding: 21px 14px;
  &:hover{
    color: red;
  }
}.badges{
  position: absolute;
  bottom: 15px;
  left: 0;
}.badge{
  padding: 5px 10px;
  color: white;
  font-weight: 700;
  text-transform: capitalize;
}.badge.discount{
  background-color: red;
}.badge.tag{
  background-color: green;
}.product-name{
  font-weight: 700;
  text-transform: uppercase;
}.price{
  font-size: .9rem;
}.price span{
  color: red;;
  font-weight: 700;
}

.card .card-images:hover .secondary-image{
  display: block;
}

</style>
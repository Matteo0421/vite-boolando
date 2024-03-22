<script>
import db from '../assets/data/db'
import Productcard from './partials/Productcard.vue'
  export default {
    components:{
      Productcard
    }
  }
</script>

<template>
  <div>
    <main>
      <div class="container ">
        <div class="row ">

            <!-- CARD  -->
            <Productcard  
            v-for="product in products"
            :key="product.id"
            :productImage="../../assets/img/products.frontImage"
            productPrice=""
            />
            <!-- /CARD  -->
            
        </div>
      </div>
    </main>
  </div>
</template>


<style lang="scss" scoped>

main{
  padding-top: 120px;
}
</style>
<script>
import db from '../assets/data/db'
import Productcard from './partials/Productcard.vue'
  export default {
    data(){
      return{
        db
      }
    },
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
            v-for="product in db"
            :key="product.id"
            :productImage="'src/assets/img' + product.frontImage"
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
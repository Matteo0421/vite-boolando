<script>
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
      <div class="container">
        <Productcard />

      </div>
    </main>
  </div>
</template>


<style lang="scss" scoped>

main{
  width: 100%;
  height: 800px;
}

</style>
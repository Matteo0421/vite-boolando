<script>
  export default {
    
  }
</script>

<template>
  <div>
    <header>
      <div class="container ">
        <div class="row justify-beetween align-center  ">
          <div class="col ">
            <nav>
              <ul class="main-menu">
                <li><a href="#">uomo</a></li>
                <li><a href="#">donna</a></li>
                <li><a href="#">bambino</a></li>
              </ul>
            </nav>
          </div>
          <div class="col logo ">
            <img src="/boolean-logo.png" alt="Logo">
          </div>
          <div class="col ">
            <nav>
              <ul class="social-menu">
                <li><a href="#"><i class="fa-regular fa-user"></i></a></li>
                <li><a href="#"><i class="fa-regular fa-heart"></i></a></li>
                <li><a href="#"><i class="fa-solid fa-bag-shopping"></i></a></li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;


header{
  position: fixed;
  z-index: 999;
  width: 100%;
  height: 80px;
  background-color: $my-primary-color ;
  box-shadow: 0 1px 3px rgba(128, 128, 128, 0.896);
  .container{
    height: 100%;
  } .row{
    height: 100%;
  }

}

.main-menu{
  display: flex;
  list-style: none;
} a{
  font-weight: 700;
  color: white;
  text-transform: capitalize;
  text-decoration: none;
  padding-right: 15px;
  &:hover{
  text-decoration: underline;
}
}


.social-menu{
  display: flex;
  list-style: none;
  justify-content: flex-end;

} a{
  font-weight: 700;
  color: white;
  text-transform: capitalize;
  text-decoration: none;
  padding-right: 15px;
  padding: 0 3px;

}


header .logo{
  width: 170px;
}

</style>
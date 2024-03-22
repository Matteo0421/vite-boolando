<script>
  export default {
    
  }
</script>

<template>
  <div>
    <footer>
      <div class="container">
        <div class="bottom-bar">
      <div class="row justify-beetween align center d-flex">
        <div class="info">
          <h4>Boolando s.r.l.</h4>
          <!-- nav -->
          <nav class="menu">
            <ul>
              <li>
                <a href="#">Informazioni legali</a>
              </li>
              <li>
                <a href="#">Informativa sulla privacy</a>
              </li>
              <li>
                <a href="#">Diritto di recesso</a>
              </li>
            </ul>
          </nav>
        <!-- /nav -->
        </div>

        <div class="social">
          <span>Trovaci anche su</span>
          <!-- nav -->
          <nav class="menu">
            <ul>
              <li>
                <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
              </li>
              <li>
                <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
              </li>
              <li>
                <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
              </li>
              <li>
                <a href="#"><i class="fa-brands fa-square-pinterest"></i></a>
              </li>
              <li>
                <a href="#"><i class="fa-brands fa-square-youtube"></i></a>
              </li>
            </ul>
          </nav>
          <!-- /nav -->
        </div>
      </div>
    </div>
      </div>
    </footer>

  </div>
</template>


<style lang="scss" scoped>



footer{
  width: 100%;
  background-color: #1A1A1A;
  color: white;
  height: 90px;

}ul{
  display: flex;
  list-style: none;
  justify-content: space-between;
}a{
  color: white;
  text-decoration: none;
  margin-right: 10px;
  font-size: .8rem;

}a:hover{
  text-decoration: underline;
}

</style>
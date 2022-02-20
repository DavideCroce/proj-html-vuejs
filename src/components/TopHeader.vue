<template>
  <div class="topheader container">
          <div class="row">
              <div class="col-3 d-flex align-items-center">
                    <img src="../assets/img/dark-logo.png" alt="">
              </div>
              <div class="col-6">
                  <nav>
                      <ul class="d-flex justify-content-around align-items-center mt-4">
                          <li>Home <i class="fas fa-chevron-down"></i></li>
                          <li>Pages <i class="fas fa-chevron-down"></i></li>
                          <li>Courses <i class="fas fa-chevron-down"></i></li>
                          <li>Features <i class="fas fa-chevron-down"></i></li>
                          <li>Blog <i class="fas fa-chevron-down"></i></li>
                          <li>Shop <i class="fas fa-chevron-down"></i></li>
                      </ul>
                  </nav>
              </div>
              <div class="col-2 d-flex justify-content-around align-items-center ms-5">
                  <i class="fab fa-twitter"></i>
                  <i class="fab fa-facebook-f"></i>
                  <i class="fab fa-instagram"></i>
                  <i class="fab fa-linkedin"></i>
              </div>
          </div>
      </div>
</template>

<script>
export default {
name: "TopHeader",
}
</script>

<style scoped lang="scss">
.fa-chevron-down{
    font-size: 10px;
}
ul{
    list-style-type: none;
    li{
        align-self: center;
    }
}
img{
    width: 200px;
    vertical-align: top;
}
li:hover, i:hover, img:hover{
    cursor: pointer;
}
</style>
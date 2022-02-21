<template>
  <div class="topheader container">
          <div class="row">
              <div class="col-6 col-sm-6 col-md-6 col-lg-3 d-flex align-items-center">
                    <img src="../assets/img/dark-logo.png" alt="">
              </div>
              <div class="col-md-6 col-sm-6 col-6 menu" >
                  <nav>
                      <ul class="d-flex justify-content-around align-items-center mt-4 classic-nav">
                          <li>Home <i class="fas fa-chevron-down"></i></li>
                          <li>Pages <i class="fas fa-chevron-down"></i></li>
                          <li>Courses <i class="fas fa-chevron-down"></i></li>
                          <li>Features <i class="fas fa-chevron-down"></i></li>
                          <li>Blog <i class="fas fa-chevron-down"></i></li>
                          <li>Shop <i class="fas fa-chevron-down"></i></li>
                      </ul>
                      <div class="vertical-menu">
                          <i class="fas fa-bars"></i>
                          <div class="vertical-nav">
                                <ul class="d-flex vertical-ul flex-row">
                                    <li> <i class="fas fa-chevron-down"></i>  Home</li>
                                    <li> <i class="fas fa-chevron-down"></i>  Pages</li>
                                    <li> <i class="fas fa-chevron-down"></i>  Courses</li>
                                    <li> <i class="fas fa-chevron-down"></i>  Features</li>
                                    <li> <i class="fas fa-chevron-down"></i>  Blog</li>
                                    <li> <i class="fas fa-chevron-down"></i>  Shop</li>
                                </ul>
                          </div>
                      </div>
                  </nav>
              </div>
              <div class="col-2 d-flex justify-content-around align-items-center ms-5 socials">
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
.fa-bars{
    display: none;
}
.fa-chevron-down{
    font-size: 10px;
}
.classic-nav{
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

.vertical-ul{
    position: absolute;
    // background-color: #fff;
    right: 5px;
    list-style-type: none;
    padding-left: 0;
    padding: 10px;
    display: none;
    li{
        display: none;
        padding-left: 20px;
    }
}

.vertical-menu:hover .vertical-ul{
    li{
        display: block;
    }
}


@media screen and (max-width: 575px){
    .col-6{
        display: flex;
        justify-content: flex-end;
    }
    ul{
        flex-direction: column;
        li{
            display: none;
            margin: 0;
        }
    }
    .fa-bars{
        display: inline;
        font-size: 25px;
    }
    .col-2 .fab{
        display: none;
    }
    nav{
        display: flex;
        align-items: center;
        justify-content: flex-end;
        margin: 0;
    }
}
@media screen and (max-width: 767px){
    .col-6{
        display: flex;
        justify-content: flex-end;
    }
    ul{
        flex-direction: column;
        li{
            display: none;
            margin: 0;
        }
    }
    .fa-bars{
        display: inline;
        font-size: 25px;
    }
    .col-2 .fab{
        display: none;
    }
    nav{
        display: flex;
        align-items: center;
        justify-content: flex-end;
        margin: 0;
    }
}
@media screen and (max-width: 991px){
    .socials{
        display: none;
        .fab{
            display: none;
        }
    }
    .classic-nav{
        li{
        padding: 0 12px;
        .fas{
            display:none;
        }
    }
    }
}
</style>
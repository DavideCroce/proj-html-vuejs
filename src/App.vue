<template>
<div class="maxCoach">
  <header>
    <Header/>
  </header>
  <main>
    <Main/>
  </main>
  <footer>
    <div class="main-footer">
      <div class="footer container">
      <div class="row things">
        <div class="col-5">
          <p class="title"><strong>Address</strong></p>
          <p class="gray">382 NE 191st St # 87394 Miami, FL 33179-3899</p>
          <p class="gray">+1 (305) 574-9909 (9am - 5pm EST, Monday - Friday)</p>
          <p class="gray">support@maxcoach.com</p>
          <p class="gray socials"><i class="fab fa-facebook-square"></i>  <i class="fab fa-twitter"></i>  <i class="fab fa-instagram"></i>  <i class="fab fa-linkedin"></i></p>
        </div>
        <div class="col-5 container">
          <div class="row">
            <div class="col-4">
              <p class="title"><strong>Explore</strong></p>
              <ul>
                <li class="gray">Start here</li>
                <li class="gray">Blog</li>
                <li class="gray">About us</li>
              </ul>
            </div>
            <div class="col-4">
              <p class="title invisible"><strong>Explore</strong></p>
              <ul>
                <li class="gray">Success story</li>
                <li class="gray">Courses</li>
                <li class="gray">Contact us</li>
              </ul>
            </div>
            <div class="col-4">
              <p class="title"><strong>Information</strong></p>
              <ul>
                <li class="gray">Membership</li>
                <li class="gray">Purchase giuse</li>
                <li class="gray">Privacy policy</li>
                <li class="gray">Terms of service</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="credits d-flex justify-content-center gray">
        <p><i class="far fa-copyright"></i> 2020 Maxcoach. All Rights Reserved</p>
      </div>
    </div>
    <div class="up-page text-center">
        <i class="fas fa-arrow-up"></i>
      </div>
    </div>
  </footer>
</div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
export default {
  name: 'App',
  components: {
    Header,
    Main,
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0 auto;
  box-sizing: border-box;
}

body{
  font-family: 'Josefin Sans', sans-serif;
}
footer{
  background-color: #171621;
  padding-top: 60px;
}

.things{
  padding-bottom: 50px;
}
.main-footer{
    position: relative;
}
.footer{
  .title{
    color: white;
  }
  .gray{
    color: gray;
    font-size: 14px;
    line-height: 22px;
  }
  .socials{
    font-size: 25px;
    .fab{
      padding-right: 20px;
    }
  }
  .invisible{
    opacity: 0;
  }
  ul{
    list-style-type: none;
    padding-left: 0;
    li{
      padding: 5px 0;
    }
  }
}
.credits{
  padding-bottom: 40px;
}
.up-page{
  color: white;
  background-color: #20ac97;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  bottom: 10px;
  right: 10px;
  position: absolute;
  .fas{
    padding-top: 17px;
  }
}

</style>

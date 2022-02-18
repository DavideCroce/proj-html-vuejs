<template>
  <div class="aboutme-video-player container">
          <div class="row">
              <div class="col-8 d-flex justify-content-center">
                  <img src="../assets/img/icon-youtube-play.png" alt="">
              </div>
              <div class="col-4 align-items-center">
                  <h2>"Every morning you have two choices: continue to sleep with your dreams, or wake up and chase them".</h2>
                  <img src="../assets/img/home-movation-shape-01.png" alt="">
                  <p class="name"><strong>Kaixa Stark</strong></p>
                  <p class="small">WINGMAN</p>
              </div>
          </div>
      </div>
</template>

<script>
export default {
    name:"AboutMeVideo",

}
</script>

<style scoped lang="scss">
.aboutme-video-player{
    padding-bottom: 150px;
}
.col-8{
    background-image: url(../assets/img/home-movation-video-poster-670x450.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    border-radius: 10px;
    padding: 250px 0;
    img{
        width: 120px;
    }
}
.col-4{
    height: 100%;
    padding: 60px;
    h2{
        font-family: 'Playfair Display', serif;
        padding-bottom: 50px;
        font-size: 25px;
        line-height: 50px;
    }
    img{
        padding-bottom: 20px;
    }
    .name{
        font-size: 20px;
    }
    .small{
        font-size: 12px;
        color: grey;
    }
}
</style>
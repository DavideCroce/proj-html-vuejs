<template>
  <div class="aboutme-video-player container">
          <div class="row">
              <div class="col-12 col-sm-12 col-md-8 d-flex justify-content-center align-items-center video-player">
                  <img class="yt-button" src="../assets/img/icon-youtube-play.png" alt="">
              </div>
              <div class="col-12 col-sm-12 col-md-4 align-items-center description">
                  <h2>"Every morning you have two choices: continue to sleep with your dreams, or wake up and chase them".</h2>
                  <img src="../assets/img/home-movation-shape-01.png" alt="">
                  <p class="name"><strong>Kaixa Stark</strong></p>
                  <p class="small">WINGMAN</p>
                  <a href="https://www.youtube.com/watch?v=1JXmzQAmBMc" target="_blank"><p class="name">Qui il link al video</p></a>
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
.yt-button:hover{
    cursor: pointer;
}
.aboutme-video-player{
    padding-bottom: 150px;
}
.video-player{
    background-image: url(../assets/img/home-movation-video-poster-670x450.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    border-radius: 10px;
    // padding: 250px 0;
    img{
        width: 20%;
    }
}
.description{
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
@media screen and (max-width: 575px){
    .video-player{
        height: 450px;
        background-position: center;
        img{
            height: 17%;
        }
    }
}
@media screen and (max-width: 767px){
    .video-player{
        background-position: center;
        height: 450px;
        img{
            height: 17%;
        }
    }
}
</style>
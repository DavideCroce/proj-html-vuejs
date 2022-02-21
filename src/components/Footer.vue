<template>
  <div class="main-footer">
      <div class="footer container">
      <div class="row">
        <div class="col-8 col-sm-8 col-md-5 text-start address">
          <Things/>
        </div>
        <div class="col-12 col-sm-12 col-md-5 container other-u-list justify-content-center">
          <div class="row">
              <Explore/>
              <Other/>
              <Information/>
          </div>
        </div>
      </div>
      <div class="credits d-flex justify-content-center gray">
        <p><i class="far fa-copyright"></i> 2020 Maxcoach. All Rights Reserved</p>
      </div>
    </div>
    <div class="up-page text-center" @click="scrollToTop">
        <i class="fas fa-arrow-up"></i>
      </div>
    </div>
</template>

<script>
import Things from "./Things.vue";
import Explore from "./Explore.vue";
import Other from "./Other.vue";
import Information from "./Information.vue";
export default {
name: "Footer",
components:{
    Things,
    Explore,
    Other,
    Information,
},
methods:{
scrollToTop(){
  window.scrollTo(0,0)
}
}
}
</script>

<style scoped lang="scss">
.gray{
    color: gray;
    font-size: 14px;
    line-height: 22px;
}
.main-footer{
  position: relative;
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
.up-page:hover{
  cursor: pointer;
}
.other-u-list{
  display: flex;
  justify-content: center;
  padding-bottom: 50px;
}
.address{
  padding-bottom: 50px;
}

// @media screen and (max-width: 575px){
//   .main-footer{
//     display: flex;
//     justify-content: center;
//      flex-direction: column;
//    }
// }
</style>
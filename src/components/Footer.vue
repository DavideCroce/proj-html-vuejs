<template>
  <div class="main-footer">
      <div class="footer container">
      <div class="row">
        <Things/>
        <div class="col-5 container">
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
    <div class="up-page text-center">
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
</style>
<template>
  <div class="real-stories">
    <Stories/>
        <div class="circle text-center align-items-center">
          <div class="gray"><i class="fas fa-caret-up"></i></div>
          <div class="counter">1/4</div>
          <div class="gray"><i class="fas fa-caret-down"></i></div>
        </div>
        <div class="image-bg col-5"></div>
      </div>
</template>

<script>
import Stories from "./Stories.vue";
export default {
name: "Slider",
components:{
    Stories,
},
}
</script>

<style scoped lang="scss">
.real-stories{
  display: flex;
  flex-direction: row;
  position: relative;

}
.image-bg{
  background-image: url(../assets/img/home-movation-testimonial-image.jpg);
  height: 640px; 
  background-repeat: no-repeat;
}
.circle{
  width: 80px;
  height: 80px;
  background-color: white;
  border-radius: 50%;
  position: absolute;
  top: 50%;
  right: 39.5%;
  margin-left: 50px;
  .fa-caret-up{
    padding-top: 5px;
  }
  .gray{
    color: rgb(156, 156, 156);
  }
}
</style>
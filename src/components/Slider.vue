<template>
  <div class="real-stories d-flex">
    <Stories :item="slide" v-for="(slide, index) in slides" :key="slide.name" :index="index" :currentIndex="currentIndex"/>
    <div class="circle text-center align-items-center">
          <div class="gray"><i class="fas fa-caret-up" @click="before"></i></div>
          <div class="counter" v-for="(numb,index) in numbs" :key="numb.number" v-show="currentIndex === index">{{numb.number}}/4</div>
          <div class="gray"><i class="fas fa-caret-down" @click="after"></i></div>
    </div>
    <div class="image-bg col-12 col-sm-12 col-md-12 col-lg-5"></div>
  </div>
</template>

<script>
import Stories from "./Stories.vue";
export default {
name: "Slider",
components:{
  Stories,
},
data(){
  return{
    currentIndex: 0,
    slides:[
      {
        story: 'I am free to learn my own pace, follow my own schedule and choose the subject I want to learn from syllabus. Great study portal for people like me.',
        pic: '02',
        name:'Mina Hollace',
        class:'/Freelancer',
      },
      {
        story: "Concentrate all your thoughts upon the work in hand. The sun's rays do not burn until brought to a focus.",
        pic: '01',
        name:'Terry Raynor',
        class:'/Soldier',
      },
      {
        story: "One of the best pieces of advice I ever got was from a horse master. He told me to go slow to go fast. I think that applies to everything in life.",
        pic: '03',
        name:'Martin Larsson',
        class:'/ProPlayer',
      },
      {
        story: "Developing a good work ethic is key. Apply yourself at whatever you do, whether you're a janitor or taking your first summer job because that work ethic will be reflected in everything you do in life.",
        pic: '04',
        name:'Nathan Drake',
        class:'Explorer',
      }
    ],
    numbs:[
      {number: '1'},
      {number: '2'},
      {number: '3'},
      {number: '4'},
    ],
  }
},
methods:{
  after(){
    if(this.currentIndex >= this.slides.length - 1){
      this.currentIndex = 0;
    }else{
      this.currentIndex++;
    }
  },
  before(){
    if(this.currentIndex <= 0){
      this.currentIndex = this.slides.length - 1;
    }else{
      this.currentIndex--;
    }
  },
}
}
</script>

<style scoped lang="scss">
.real-stories{
  display: flex;
  flex-direction: row;
  position: relative;
  margin-bottom: 150px;
  max-width: 1400px;
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
  .gray:hover{
    cursor: pointer;
  }
}
@media screen and (max-width: 575px){
  .circle{
    top: 95%;
    align-self: center;
    margin-right: 40px;
  }
  .image-bg{
    display: none;
  }
}
@media screen and (max-width: 767px){
  .circle{
    top: 95%;
    left: 39%;
  }
  .image-bg{
    display: none;
  }
}
@media screen and (max-width: 991px){
  .circle{
    top: 95%;
    left: 42%;
  }
  .image-bg{
    display: none;
  }
}
</style>
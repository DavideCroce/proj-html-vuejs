<template>
  <div class="slider col-7" v-show="currentIndex === index">
        <div class="content text-center">
            <div class="title-green">REAL STORIES</div>
            <div class="story">{{item.story}}</div>
            <div class="user-pic">
              <img :src="require(`../assets/img/testimonial-avata-${item.pic}.jpg`)" alt="">
            </div>
            <div class="user-name">{{item.name}}</div>
            <div class="user-class">/{{item.class}}</div>
        </div>
  </div>
</template>

<script>
export default {
name: "Stories",
props: ['item', 'index', 'currentIndex'],
}
</script>

<style scoped lang="scss">
.slider{
  display: flex;
  align-items: center;
    background-image: url(../assets/img/background-pattern-wavify.png);
    background-repeat: repeat;
    background-color: #dfdfdf;
}
.content{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 50%;
    img{
      height: 100px;
      border-radius: 50%;
      padding-bottom: 10px;
    }
    .story{
      font-size: 30px;
      padding-bottom: 50px;
    }
    .user-name{
      font-size: 20px;
      font-weight: 400px;
      padding-bottom: 10px;
    }
    .user-class{
      font-size: 14px;
      color: grey;

    }
    .title-green{
      font-size: 15px;
      color: #20ac97;
      padding-bottom: 30px;
    }
}
.slider:hover .user-pic,.user-class,.user-name{
  cursor: pointer;
}

</style>
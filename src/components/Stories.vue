<template>
  <div class="slider col-7">
          <div class="content text-center">
            <div class="title-green">REAL STORIES</div>
            <div class="story">I am free to learn my own pace, follow my own schedule and choose the subject I want to learn from syllabus. Great study portal for people like me.</div>
            <div class="user-pic">
              <img src="../assets/img/testimonial-avata-02.jpg" alt="">
            </div>
            <div class="user-name">Mina Hollace</div>
            <div class="user-class">/Freelancer</div>
          </div>
        </div>
</template>

<script>
export default {
name: "Stories",
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
</style>
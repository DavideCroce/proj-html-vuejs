<template>
  <div class="online-courses">
        <p class="sub-title text-center">BEGIN YOUR JOURNEY AT MAXCOACH</p>
        <h1 class="text-center">Lastest <span class="green">Online Courses</span></h1>
        <CoursesCard/>
        <div class="all-courses-button container d-flex justify-content-center mt-3">
          <button>View all courses  <i class="fas fa-arrow-right"></i></button>
        </div>
      </div>
</template>

<script>
import CoursesCard from "./CoursesCard.vue";
export default {
name: "OnlineCourses",
components: {
  CoursesCard,
},

}
</script>

<style scoped lang="scss">

button{
    padding: 15px 60px;
     background-color: #20ac97;
    color: white;
    font-weight: 500;
    border: none;
    border-radius: 5px;
    font-size: 13px;
    margin-top: 20px;
}
button:hover{
  background-color: #3f3a64;
}
.online-courses{
  margin-bottom: 100px;
  .sub-title{
      font-size: 14px;
      color: grey;
  }
  h1{
    font-family: 'Playfair Display', serif;
    padding-bottom: 50px;
    .green{
      color: #20ac97;
    }
  }
}
</style>
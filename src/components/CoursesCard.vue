<template>
  <div class="courses container justify-content-center">
          <div class="row">
            <div v-for="course in courses" :key="course.lenght" class="col-4">
              <img :src="require(`../assets/img/motivation-course-${course.image}-480x298.jpg`)" alt="">
              <div class="card-info">
                <p class="price">{{course.pricebig}}.<span class="smaller">{{course.pricesmall}}</span></p>
                <h4>{{course.description}}</h4>
                <div class="info">
                  <span class="lessons"><i class="far fa-file-alt"></i>  {{course.lessons}} Lessons</span>
                  <span class="students"><i class="far fa-user"></i> {{course.students}} Students</span>
                </div> 
              </div>
          </div>
          
          </div>
    </div>
</template>

<script>
export default {
name: "CoursesCard",
data(){
  return {
    courses: [
      {
        image: '06',
        pricebig: '$30',
        pricesmall: '00',
        description: 'How to be Successful: Create A Growth For Success',
        lessons: '3',
        students: '50',
      },
      {
        image: '05',
        pricebig: '$30',
        pricesmall: '00',
        description: 'How to Build Confidance in Your Abilities',
        lessons: '1',
        students: '50',
      },
      {
        image: '04',
        pricebig: '$20',
        pricesmall: '00',
        description: 'Productivity Machine - Focus in a Distracted World',
        lessons: '5',
        students: '50',
      },
      {
        image: '03',
        pricebig: '$20',
        pricesmall: '00',
        description: 'Effective Time Management Mastery - Complete Guide',
        lessons: '18',
        students: '50',
      },
      {
        image: '02',
        pricebig: '$25',
        pricesmall: '99',
        description: 'Body Language Secrets for Entrepreneurs',
        lessons: '19',
        students: '50',
      },
      {
        image: '01',
        pricebig: '$19',
        pricesmall: '99',
        description: 'Management Skills: The Science od Leadership',
        lessons: '17',
        students: '50',
      },
    ]
  }
}
}
</script>

<style scoped lang="scss">
.col-4{
  padding: 20px 15px;
  border-radius: 20px;
  img{
    width: 100%;
  }
  .card-info{
    padding: 25px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    .price{
      font-size: 25px;
      color: #20ac97;
      font-weight: 500;
      padding-bottom: 10px;
      .smaller{
        font-size: 20px;
      }
    }
    h4{
      padding-bottom: 20px;
    }
    .info{
      color: grey;
      font-size: 14px;
    }
    .students{
      padding-left: 30px;
    }
  }
}
.col-4:hover .card-info{
  background-color: rgb(233, 233, 233);
}
.courses:hover{
  cursor: pointer;
}
</style>
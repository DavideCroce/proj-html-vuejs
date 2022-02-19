<template>
  <div class="courses container justify-content-center">
          <div class="row">
            <div class="col-4">
              <img src="../assets/img/motivation-course-06-480x298.jpg" alt="">
              <div class="card-info">
                <p class="price">$30.<span class="smaller">00</span></p>
                <h4>How to be Successful: Create A Growth For Success</h4>
                <div class="info">
                  <span class="lessons"><i class="far fa-file-alt"></i>  3 Lessons</span>
                  <span class="students"><i class="far fa-user"></i> 50 Students</span>
                </div> 
              </div>
          </div>
          <div class="col-4">
              <img src="../assets/img/motivation-course-05-480x298.jpg" alt="">
              <div class="card-info">
                <p class="price">$30.<span class="smaller">00</span></p>
                <h4>How to Build Confidance in Your Abilities</h4>
                <div class="info">
                  <span class="lessons"><i class="far fa-file-alt"></i>  1 Lesson</span>
                  <span class="students"><i class="far fa-user"></i> 50 Students</span>
                </div> 
              </div>
          </div>
          <div class="col-4">
              <img src="../assets/img/motivation-course-04-480x298.jpg" alt="">
              <div class="card-info">
                <p class="price">$20.<span class="smaller">00</span></p>
                <h4>Productivity Machine - Focus in a Distracted World</h4>
                <div class="info">
                  <span class="lessons"><i class="far fa-file-alt"></i>  5 Lessons</span>
                  <span class="students"><i class="far fa-user"></i> 50 Students</span>
                </div> 
              </div>
          </div>
          <div class="col-4">
              <img src="../assets/img/motivation-course-03-480x298.jpg" alt="">
              <div class="card-info">
                <p class="price">$20.<span class="smaller">00</span></p>
                <h4>Effective Time Management Mastery - Complete Guide</h4>
                <div class="info">
                  <span class="lessons"><i class="far fa-file-alt"></i>  18 Lessons</span>
                  <span class="students"><i class="far fa-user"></i> 50 Students</span>
                </div> 
              </div>
          </div>
          <div class="col-4">
              <img src="../assets/img/motivation-course-02-480x298.jpg" alt="">
              <div class="card-info">
                <p class="price">$25.<span class="smaller">99</span></p>
                <h4>Body Language Secrets for Entrepreneurs</h4>
                <div class="info">
                  <span class="lessons"><i class="far fa-file-alt"></i>  19 Lessons</span>
                  <span class="students"><i class="far fa-user"></i> 50 Students</span>
                </div> 
              </div>
          </div>
          <div class="col-4">
              <img src="../assets/img/motivation-course-01-480x298.jpg" alt="">
              <div class="card-info">
                <p class="price">$19.<span class="smaller">99</span></p>
                <h4>Management Skills: The Science od Leadership</h4>
                <div class="info">
                  <span class="lessons"><i class="far fa-file-alt"></i>  17 Lessons</span>
                  <span class="students"><i class="far fa-user"></i> 50 Students</span>
                </div> 
              </div>
          </div>
          </div>
    </div>
</template>

<script>
export default {
name: "CoursesCard",
}
</script>

<style scoped lang="scss">
.col-4{
  padding: 20px 15px;
  border-radius: 20px;
  img{
    width: 400px;
  }
  .card-info{
    padding: 25px;
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
</style>
<template>
  <div class="update-card container">
          <div class="row">
            <div class="col-3">
              <img src="../assets/img/motivation-blog-04-480x325.jpg" alt="">
              <div class="date"><i class="far fa-calendar"></i> May 13, 2020</div>
              <h3>How to Stay True to Your Personal Brand</h3>
              <p class="description">When it comes to your busines or career, you want ...</p>
            </div>
              <div class="col-3">
              <img src="../assets/img/motivation-blog-03-480x325.jpg" alt="">
              <div class="date"><i class="far fa-calendar"></i> May 13, 2020</div>
              <h3>5 Vital Lessons in 5 Years of Freelancing</h3>
              <p class="description">Being self-emplyes and working form home it's easy to get ...</p>
            </div>
              <div class="col-3">
              <img src="../assets/img/motivation-blog-02-480x325.jpg" alt="">
              <div class="date"><i class="far fa-calendar"></i> May 13, 2020</div>
              <h3>11 Super Useful Tips for Small-Business Owners</h3>
              <p class="description">Being a small-business owner poses a ton of challenges. We ...</p>
            </div>
              <div class="col-3">
              <img src="../assets/img/motivation-blog-01-480x325.jpg" alt="">
              <div class="date"><i class="far fa-calendar"></i> May 13, 2020</div>
              <h3>How to Give Yourself Grace to Start Again</h3>
              <p class="description">Forgive yourself for bad habits you may have started or ...</p>
            </div>
          </div>
        </div>
</template>

<script>
export default {
name: "UCard",
}
</script>

<style scoped lang="scss">
.update-card{
  padding-top: 50px;
  img{
    width: 300px;
    border-radius: 10px;
    margin-bottom: 20px;
  }
  .date{
    font-size: 13px;
    color: gray;
    padding-bottom: 20px;
  }
  h3{
    font-size: 23px;
  }
  .description{
    color: gray;
    padding-top: 20px;
  }
}
</style>
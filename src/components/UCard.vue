<template>
  <div class="update-card container">
          <div class="row">
            <div v-for="update in updates" :key="update.lenght" class="col-3">
              <img :src="require(`../assets/img/motivation-blog-${update.image}-480x325.jpg`)" alt="">
              <div class="date"><i class="far fa-calendar"></i> {{update.date}}</div>
              <h3>{{update.title}}</h3>
              <p class="description">{{update.description}} ...</p>
          </div>
        </div>
        </div>
</template>

<script>
export default {
name: "UCard",
data(){
  return{
    updates: [
      {
        image: '04',
        date: 'May 13, 2020',
        title: 'How to Stay True to Your Personal Brand',
        description: 'When it comes to your busines or career, you want',
      },
      {
        image: '03',
        date: 'May 13, 2020',
        title: '5 Vital Lessons in 5 Years of Freelancing',
        description: "Being self-emplyes and working form home it's easy to get",
      },
      {
        image: '02',
        date: 'May 13, 2020',
        title: '11 Super Useful Tips for Small-Business Owners',
        description: 'Being a small-business owner poses a ton of challenges. We',
      },
      {
        image: '01',
        date: 'May 13, 2020',
        title: 'How to Give Yourself Grace to Start Again',
        description: 'Forgive yourself for bad habits you may have started or',
      },
    ]
  }
}
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
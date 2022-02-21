<template>
<div class="aboutme-text container">
          <p class="about-me">ABOUT ME</p>
          <div class="row">
              <div class="col-12 col-sm-12 col-md-6 title d-flex justify-content-start">
                  <h1>How to Be an Aplha Male: The 15 Habits of True Alphas</h1>
              </div>
              <div class="col-12 col-sm-12 col-md-6">
                  <p class="strong">Want to learn how to be <span class="green">an alpha male</span>? How to be more masculine? How to be the man you've always wanted to be?</p>
                  <p class="grey">Your goal is to show the consistency of business, core values, and customer care. Punctualty, responsibility, individuality, accuracy, enthusiasm - you have to clearly explain how these qualities are applicable to your work. And the important thing is you to love what you do.</p>
              </div>
          </div>
      </div>
</template>

<script>
export default {
name:"AboutMeTxt",
}
</script>

<style scoped lang="scss">
.aboutme-text{
    padding-bottom: 100px;
    .about-me{
        color: #20ac97;
        font-weight: 500;
    }
    .title{
        padding-right: 200px;
        h1{
            font-family: 'Playfair Display', serif;
        }
    }
    .strong{
        font-weight: 600;
        font-size: 17px;
        .green{
            color: #20ac97;
        }
    }
    .grey{
        color: grey;
        font-size: 15px;
    }
}
</style>
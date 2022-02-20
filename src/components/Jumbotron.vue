<template>
  <div class="jumbotron container">
          <div class="row">
                <div class="col-5 pb-5 ">
                    <p class="pt-5">I'M WINGMAN</p>
                    <h1>Peace On Earth A Wonderful Wish But No Way</h1>
                    <p>Success isn't overnight. It's when everyday you get a little better than the day before. It all adds up.</p>
                    <button>Get Started For Free <i class="fas fa-arrow-right"></i></button>
                </div>
                <div class="col-7 images d-flex justify-content-end">
                    <img class="man" src="../assets/img/home-movation-hero-image.png" alt="">
                </div>
          </div>
      </div>
</template>

<script>
export default {
name: "Jumbotron",
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

h1{
    font-family: 'Playfair Display', serif;
    padding: 10px 0;
    font-size: 60px;
    margin-bottom: 20px;
}

.jumbotron{
    padding: 0 50px;
    padding-top: 50px;
}

.images{
    background-image: url(../assets/img/home-movation-shape-face.png);
    background-repeat: no-repeat;
    background-position-y: 200px;
    background-position-x: 100px;
}
</style>
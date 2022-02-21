<template>
  <div class="sponsors container">
        <div class="row">
          <div class="col-6 col-sm-6 col-md-4 col-lg-2 d-flex align-items-center sponsor" v-for="sponsor in sponsors" :key="sponsor.image">
            <img :src="require(`../assets/img/client-logo-${sponsor.image}-primary.png`)" alt="">
          </div>
        </div>
      </div>
</template>

<script>
export default {
name: "Sponsors",
data(){
  return{
    sponsors:[
      {
        image:'05',
      },
      {
        image:'06',
      },
      {
        image:'07',
      },
      {
        image:'04',
      },
      {
        image:'03',
      },
      {
        image:'02',
      },
    ]
  }
}
}
</script>

<style scoped lang="scss">
.sponsors{
  margin-bottom: 150px;
}
.sponsor{
  filter: grayscale(70%);
  opacity: 0.5;
}
.sponsor:hover{
  cursor: pointer;
}

@media screen and (max-width: 575px){
  .sponsor{
    margin-bottom: 40px;
  }
}
@media screen and (max-width: 767px){
  .sponsor{
    margin-bottom: 40px;
  }
}
@media screen and (max-width: 991px){
  .sponsor{
    margin-bottom: 40px;
  }
}
</style>
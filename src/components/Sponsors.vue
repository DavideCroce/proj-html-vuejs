<template>
  <div class="sponsors container">
        <div class="row">
          <div class="col-2 d-flex align-items-center" v-for="sponsor in sponsors" :key="sponsor.image">
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
.col-2{
  filter: grayscale(70%);
  opacity: 0.5;
}
.col-2:hover{
  cursor: pointer;
}
</style>
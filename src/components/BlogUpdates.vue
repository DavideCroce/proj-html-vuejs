<template>
  <div class="blog-update container">
        <p class="subtitle">BLOG UPDATED</p>
        <h1>Interesting <span class="green">articles updated</span>daily</h1>
        <UCard/>
        <div class="d-flex justify-content-center pt-5">
          <a class="view-more" href="#">VIEW ALL POSTS</a>
        </div>
      </div>
</template>

<script>
import UCard from "./UCard.vue";
export default {
name: "BlogUpdates",
components: {
  UCard,
}
}
</script>

<style scoped lang="scss">
.blog-update{
  margin-bottom: 150px;
}
.view-more{
  color: #20ac97;
  padding: 5px;
  text-decoration: none;
  border-bottom: #20ac97 solid 2px;
  font-size: 13px;
  font-weight: bold;
}
</style>
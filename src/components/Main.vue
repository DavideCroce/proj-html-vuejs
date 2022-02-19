<template>
  <div class="main">
      <Stats/>
      <AboutMeTxt/>
      <AboutMeVideo/>
      <OnlineCourses/>
      <BookStore/>
  </div>
</template>

<script>
import Stats from "./Stats.vue";
import AboutMeTxt from "./AboutMeTxt.vue";
import AboutMeVideo from "./AboutMeVideo.vue";
import OnlineCourses from "./OnlineCourses.vue";
import BookStore from "./BookStore.vue";
export default {
name: "Main",
components: {
    Stats,
    AboutMeTxt,
    AboutMeVideo,
    OnlineCourses,
    BookStore,
}
}
</script>

<style scoped lang="scss">

  

</style>
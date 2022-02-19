<template>
  <div class="main">
      <Stats/>
      <AboutMeTxt/>
      <AboutMeVideo/>
      <OnlineCourses/>
      <BookStore/>
      <Sponsors/>
      <Slider/>
      <BlogUpdates/>
  </div>
</template>

<script>
import Stats from "./Stats.vue";
import AboutMeTxt from "./AboutMeTxt.vue";
import AboutMeVideo from "./AboutMeVideo.vue";
import OnlineCourses from "./OnlineCourses.vue";
import BookStore from "./BookStore.vue";
import Sponsors from "./Sponsors.vue";
import Slider from "./Slider.vue";
import BlogUpdates from "./BlogUpdates.vue";
export default {
name: "Main",
components: {
    Stats,
    AboutMeTxt,
    AboutMeVideo,
    OnlineCourses,
    BookStore,
    Sponsors,
    Slider,
    BlogUpdates,
}
}
</script>

<style scoped lang="scss">

</style>
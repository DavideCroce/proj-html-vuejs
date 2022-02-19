<template>
  <div class="main">
      <Stats/>
      <AboutMeTxt/>
      <AboutMeVideo/>
      <OnlineCourses/>
  </div>
</template>

<script>
import Stats from "./Stats.vue";
import AboutMeTxt from "./AboutMeTxt.vue";
import AboutMeVideo from "./AboutMeVideo.vue";
import OnlineCourses from "./OnlineCourses.vue";
export default {
name: "Main",
components: {
    Stats,
    AboutMeTxt,
    AboutMeVideo,
    OnlineCourses,
}
}
</script>

<style scoped lang="scss">

</style>
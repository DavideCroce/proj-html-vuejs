<template>
  <div class="main">
      <Stats/>
      <AboutMeTxt/>
      <AboutMeVideo/>
  </div>
</template>

<script>
import Stats from "./Stats.vue";
import AboutMeTxt from "./AboutMeTxt.vue";
import AboutMeVideo from "./AboutMeVideo.vue";
export default {
name: "Main",
components: {
    Stats,
    AboutMeTxt,
    AboutMeVideo,
}
}
</script>

<style scoped lang="scss">
</style>
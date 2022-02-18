<template>
  <div class="main">
      <Stats/>
      <AboutMeTxt/>
  </div>
</template>

<script>
import Stats from "./Stats.vue";
import AboutMeTxt from "./AboutMeTxt.vue";
export default {
name: "Main",
components: {
    Stats,
    AboutMeTxt,
}
}
</script>

<style scoped lang="scss">
</style>
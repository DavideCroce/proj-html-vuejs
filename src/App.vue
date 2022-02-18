<template>
<div class="maxCoach">
  <header>
    <Header/>
  </header>
</div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0 auto;
  box-sizing: border-box;
}

body{
    font-family: sans-serif;
}
</style>

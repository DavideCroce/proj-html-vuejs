<template>
<div class="maxCoach">
  <header>
    <Header/>
  </header>
  <main>
    <Main/>
  </main>
</div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
export default {
  name: 'App',
  components: {
    Header,
    Main,
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
  font-family: 'Josefin Sans', sans-serif;
}

</style>

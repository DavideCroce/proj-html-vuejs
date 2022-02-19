<template>
<div class="maxCoach">
  <header>
    <Header/>
  </header>
  <main>
    <Main/>
  </main>
  <footer>
    <Footer/>
  </footer>
</div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
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
footer{
  background-color: #171621;
  padding-top: 60px;
}


</style>

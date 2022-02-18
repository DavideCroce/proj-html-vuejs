<template>
  <div class="header">
      <TopHeader/>
      <Jumbotron/>
  </div>
</template>

<script>
import TopHeader from "./TopHeader.vue";
import Jumbotron from "./Jumbotron.vue";
export default {
name:"Header",
components:{
TopHeader,
Jumbotron,
}
}
</script>

<style scoped lang="scss">
.header{
    background-image: url(../assets/img/background-pattern-wavify.png);
    background-repeat: repeat;
    background-size: contain;
    width: 100%;
    background-color: #dfdfdf;
    padding-top: 30px;
    font-family: 'Josefin Sans', sans-serif;
}
</style>
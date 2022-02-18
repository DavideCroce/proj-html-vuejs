<template>
  <div class="stats text-center container">
      <div class="row">
        <div class="col-3">
        <h1>1.926</h1>
        <p>FINISHED SESSION</p>
      </div>
      <div class="col-3">
        <h1>100%</h1>
        <p>SATISFACTION RATE</p>
      </div>
      <div class="col-3">
        <h1>3092+</h1>
        <p>ENROLLED LEARNERS</p>
      </div>
      <div class="col-3 endborder">
        <h1>200</h1>
        <p>ONLINE INSTRUCTORS</p>
      </div>
      </div>
    </div>
</template>

<script>
export default {
name:"Stats",
}
</script>

<style scoped lang="scss">
.col-3{
  border-left: dashed lightblue 1px;
  h1{
    color: #20ac97;
  }
}

.endborder{
  border-right: dashed lightblue 1px;
}

.stats{
  padding: 200px 0;
  font-family: 'Josefin Sans', sans-serif;
}
</style>
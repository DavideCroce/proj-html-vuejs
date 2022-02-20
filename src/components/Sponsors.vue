<template>
  <div class="sponsors container">
        <div class="row">
          <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/client-logo-05-primary.png" alt="">
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/client-logo-06-primary.png" alt="">
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/client-logo-07-primary.png" alt="">
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/client-logo-04-primary.png" alt="">
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/client-logo-03-primary.png" alt="">
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="../assets/img/client-logo-02-primary.png" alt="">
          </div>
        </div>
      </div>
</template>

<script>
export default {
name: "Sponsors",
}
</script>

<style scoped lang="scss">
.sponsors{
  margin-bottom: 150px;
}
.col-2{
  filter: grayscale(70%);
  opacity: 0.5;
}
.col-2:hover{
  cursor: pointer;
}
</style>
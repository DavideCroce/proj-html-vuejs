<template>
  <div class="things">
          <p class="title"><strong>Address</strong></p>
          <p class="gray">382 NE 191st St # 87394 Miami, FL 33179-3899</p>
          <p class="gray">+1 (305) 574-9909 (9am - 5pm EST, Monday - Friday)</p>
          <p class="gray">support@maxcoach.com</p>
          <p class="gray socials"><i class="fab fa-facebook-square"></i>  <i class="fab fa-twitter"></i>  <i class="fab fa-instagram"></i>  <i class="fab fa-linkedin"></i></p>
        </div>
</template>

<script>
export default {
name: "Things"
}
</script>

<style scoped lang="scss">
.things{
  padding-bottom: 50px;
  .gray{
    color: gray;
    font-size: 14px;
    line-height: 22px;
  }
  .gray:hover{
      cursor: pointer;
  }
  .title{
    color: white;
  }
}

</style>
<template>
  <div class="col-4 information">
        <p class="title"><strong>Information</strong></p>
        <ul>
            <li class="gray">Membership</li>
            <li class="gray">Purchase giuse</li>
            <li class="gray">Privacy policy</li>
            <li class="gray">Terms of service</li>
        </ul>
    </div>
</template>

<script>
export default {
name: "Information",
}
</script>

<style scoped lang="scss">
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
ul{
    list-style-type: none;
    padding-left: 0;
    li{
      padding: 5px 0;
    }
}
.information{
  margin: 0;
}
</style>
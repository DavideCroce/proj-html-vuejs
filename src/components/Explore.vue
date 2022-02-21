<template>
  <div class="col-4 explore">
        <p class="title"><strong>Explore</strong></p>
        <ul>
            <li class="gray">Start here</li>
            <li class="gray">Blog</li>
            <li class="gray">About us</li>
        </ul>
    </div>
</template>

<script>
export default {
name: "Explore",
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
  .explore{
    margin: 0;
  }
</style>
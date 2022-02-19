<template>
  <div class="col-4 other">
        <p class="title invisible"><strong>Explore</strong></p>
        <ul>
            <li class="gray">Success story</li>
            <li class="gray">Courses</li>
            <li class="gray">Contact us</li>
        </ul>
    </div>
</template>

<script>
export default {
name: "Other",
}
</script>

<style scoped lang="scss">
.gray{
    color: gray;
    font-size: 14px;
    line-height: 22px;
}
.title{
    color: white;
  }
  .invisible{
    opacity: 0;
  }
  ul{
    list-style-type: none;
    padding-left: 0;
    li{
      padding: 5px 0;
    }
  }
</style>
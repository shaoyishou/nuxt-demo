<style lang="less" scoped>
  .layouts-blog {

    .layouts-head {
      height: 70px;
      text-align: center;
      line-height: 70px;
      border-bottom: 1px solid #888;

      > p {
        font-size: 22px;
      }
    }

    .layouts-foot {
      height: 70px;
      text-align: center;

      > p {
        font-size: 18px;
      }
    }
  }
</style>

<template>
  <div class="layouts-blog">
    <header class="layouts-head">
      <p>head</p>
    </header>

    <div class="containner">
      <nuxt/>
    </div>

    <footer class="layouts-foot">
      <p>版权</p>
    </footer>
  </div>
</template>

<script>
  export default {

  }
</script>

<template>
  <div class="main">
    <NavBar />

    <div class="content">
      <nuxt />
    </div>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar'
export default {
}
</script>

<style lang="scss" scoped>
.main {
  width: 1778px;
  height: 1000px;

  background: 0 0/800px 1000px url('~assets/images/image.png') no-repeat,
              1645px 863px/131px 135px url('~assets/images/angle.png') no-repeat,
              655px 679px/492px 319px url('~assets/images/flora_2.png') no-repeat,
              1595px 167px/184px 145px url('~assets/images/flora_3.png') no-repeat,
              1201px 921px/179px 78px url('~assets/images/stone_1.png') no-repeat,
              761px 183px/195px 164px url('~assets/images/stone_2.png') no-repeat,
              1709px 525px/67px 160px  url('~assets/images/stone_3.png') no-repeat,
              1609px 0px/167px 146px  url('~assets/images/stone_4.png') no-repeat,
              #fdfaf5;

  .content {
    padding: 40px 0 0 700px;
  }
}
</style>

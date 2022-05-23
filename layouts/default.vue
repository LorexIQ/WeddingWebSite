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
  width: 100%;
  height: 1000px;

  @media (min-width: 1100px) and (max-width: 10000px) {
    min-width: 1778px;

    background: 0 0/800px 1000px url('~assets/images/image.png') no-repeat,
    right 863px/131px 135px url('~assets/images/angle.png') no-repeat,
    655px 679px/492px 319px url('~assets/images/flora_2.png') no-repeat,
    right 167px/184px 145px url('~assets/images/flora_3.png') no-repeat,
    1201px 921px/179px 78px url('~assets/images/stone_1.png') no-repeat,
    761px 183px/195px 164px url('~assets/images/stone_2.png') no-repeat,
    right 525px/67px 160px  url('~assets/images/stone_3.png') no-repeat,
    right 0px/167px 146px  url('~assets/images/stone_4.png') no-repeat,
    #fdfaf5;
  }

  @media (min-width: 1100px) and (max-width: 1777.98px) {
    min-width: 1100px;
    min-height: 100vh;

    background: right bottom/131px 135px url('~assets/images/angle.png') no-repeat,
    left bottom/492px 319px url('~assets/images/flora_2.png') no-repeat,
    right 167px/184px 145px url('~assets/images/flora_3.png') no-repeat,
    calc(50% + 100px) bottom/179px 78px url('~assets/images/stone_1.png') no-repeat,
    calc(50% - 200px) 183px/195px 164px url('~assets/images/stone_2.png') no-repeat,
    right 525px/67px 160px  url('~assets/images/stone_3.png') no-repeat,
    right 0px/167px 146px  url('~assets/images/stone_4.png') no-repeat,
    #fdfaf5;
  }
  @media (min-width: 700px) and (max-width: 1099.98px) {
    min-width: 700px;
    min-height: 100vh;

    background: right bottom/131px 135px url('~assets/images/angle.png') no-repeat,
    left bottom/492px 319px url('~assets/images/flora_2.png') no-repeat,
    right 525px/67px 160px  url('~assets/images/stone_3.png') no-repeat,
    #fdfaf5;
  }
  @media (min-width: 200px) and (max-width: 699.98px) {
    min-height: 100vh;
    height: 100vh;

    background: right bottom/131px 135px url('~assets/images/angle.png') no-repeat,
    left bottom/492px 319px url('~assets/images/flora_2.png') no-repeat,
    right 50%/67px 160px  url('~assets/images/stone_3.png') no-repeat,
    #fdfaf5;
  }
}
</style>

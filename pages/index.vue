<template>
  <div class="main-index">
    <h1 class="names-web">Sophie &</h1>
    <h1 class="names-web second-name">Matthew</h1>
    <h2>Save <span>the</span> Date</h2>
    <span>SATURDAY<h2>22 <span>Apr.</span></h2><span>18 HS.</span></span>
    <p>invite you to join them at<br>the celebration of they married </p>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
* {
  margin: 0;
}
.main-index {
  width: 600px;
  margin: 75px 0 0 388px;

  background: 33px 37px/562px 238px url('~assets/images/flora_1.png') no-repeat;

  .names-web {
    font-family: "Playfair Display", serif;
    font-weight: 700;
    font-size: 100px;
    line-height: 94px;
  }
  .second-name {
    padding-left: 192px;
  }
  > h2 {
    font-family: "Playfair Display", serif;
    font-weight: 700;
    font-size: 64px;
    letter-spacing: -0.3px;

    padding: 106px 0 0 246px;

    > span {
      font-size: 32px;
    }
  }
  > span {
    font-family: "Poppins", serif;
    font-weight: 400;
    font-size: 25px;
    letter-spacing: 4.8px;

    padding-left: 47px;

    > span {
      font-size: 21px;
    }
    > h2 {
      font-family: "Playfair Display", serif;
      font-weight: 700;
      font-size: 100px;
      letter-spacing: 0.5px;
      line-height: 75px;

      padding-left: 41px;
      padding-right: 25px;

      display: inline;

      > span {
        font-size: 50px;
      }
    }
  }
  > p {
    font-size: 23px;
    letter-spacing: 4.5px;
    line-height: 37px;

    padding: 22px 7px 0 0;

    text-align: right;
    text-transform: uppercase;
  }
}
</style>

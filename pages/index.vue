<template>
  <div class="main-index">
    <h1 class="names-web">Sophie &</h1>
    <h1 class="names-web second-name">Matthew</h1>
    <h2>Save <span>the</span> Date</h2>
    <span>SATURDAY<h2>22 <span>Apr.</span></h2><span>18 HS.</span></span>
    <p>invite you to join them at<br>the celebration of they married </p>
    <a href=""><p>Confirm Assistance</p></a>
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
  margin: 75px 90px 0 auto;

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
  > a {
    p {
      height: 64px;
      width: 350px;
      border-radius: 32px;

      background-color: #d8d8c9;

      font-family: "Playfair Display", serif;
      font-size: 33px;
      font-weight: 700;

      text-align: center;
      line-height: 54px;

      margin: 42px 4px 0 auto;
    }
  }
  @media (min-width: 700px) and (max-width: 1777.98px) {
    margin: 75px auto;
  }
  @media (min-width: 700px) and (max-width: 1099.98px) {
    padding-top: 60px;
    justify-content: center;

    background: 33px 60px/562px 238px url('~assets/images/flora_1.png') no-repeat;
  }
  @media (min-width: 200px) and (max-width: 699.98px) {
    width: 330px;
    padding: 47px 0 0 32px;
    margin: 75px auto;

    background: 48px 63px/282px 119px url('~assets/images/flora_1.png') no-repeat;

    .names-web {
      font-family: "Playfair Display", serif;
      font-weight: 700;
      font-size: 50px;
      line-height: 46px;
    }
    .second-name {
      padding-left: 96px;
    }
    > h2 {
      font-family: "Playfair Display", serif;
      font-weight: 700;
      font-size: 32px;
      letter-spacing: -0.3px;

      padding: 53px 0 0 124px;

      > span {
        font-size: 16px;
      }
    }
    > span {
      font-family: "Poppins", serif;
      font-weight: 400;
      font-size: 12px;
      letter-spacing: 3px;

      padding-left: 23px;

      > span {
        font-size: 10px;
      }
      > h2 {
        font-family: "Playfair Display", serif;
        font-weight: 700;
        font-size: 50px;
        letter-spacing: 0.5px;
        line-height: 37px;

        padding-left: 19px;
        padding-right: 10px;

        display: inline;

        > span {
          font-size: 25px;
        }
      }
    }
    > p {
      font-size: 11px;
      letter-spacing: 2.5px;
      line-height: 18px;

      padding: 12px 64px 0 0;

      text-align: right;
      text-transform: uppercase;
    }
    > a {
      p {
        height: 50px;
        width: 250px;
        border-radius: 32px;

        background-color: #d8d8c9;

        font-family: "Playfair Display", serif;
        font-size: 20px;
        font-weight: 700;

        text-align: center;
        line-height: 46px;

        margin: 42px auto;
      }
    }
  }
}
</style>

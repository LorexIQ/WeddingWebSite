<template>
  <div class="main-block">
    <ul class="social">
      <li><a href="" class="main-image image-1"><p></p></a></li>
      <li><a href="" class="main-image image-2"><p></p></a></li>
      <li><a href="" class="main-image image-3"><p></p></a></li>
      <li><a href="" class="main-image image-4"><p></p></a></li>
    </ul>
    <ul class="nav">
      <li><nuxt-link to="/" class="elem" exact-active-class="active">Home</nuxt-link></li>
      <li><nuxt-link to="/wedding" class="elem" exact-active-class="active">Wedding</nuxt-link></li>
      <li><nuxt-link to="/ceremony" class="elem" exact-active-class="active">Ceremony</nuxt-link></li>
      <li><nuxt-link to="/contact" class="elem" exact-active-class="active">Contact</nuxt-link></li>
    </ul>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
.main-block {
  display: flex;
  flex-direction: row;
  gap: 84px;
  align-items: center;

  padding: 45px 0 0 800px;

  ul {
    margin: 0;
    padding: 0;
  }

  .social {
    display: flex;
    flex-direction: row;
    gap: 13px;

    list-style-type: none;

    .main-image p {
      margin: 0;
      width: 30px;
      height: 30px;
    }

    .image-1 p {
      background: 0 0/30px 30px url('~assets/images/Instagram.png') no-repeat;
    }
    .image-2 p {
      background: 0 0/30px 30px url('~assets/images/Facebook.png') no-repeat;
    }
    .image-3 p {
      background: 0 0/30px 30px url('~assets/images/Twitter.png') no-repeat;
    }
    .image-4 p {
      background: 0 0/30px 30px url('~assets/images/WhatsApp.png') no-repeat;
    }
  }

  .nav {
    display: flex;
    flex-direction: row;
    gap: 47px;
    padding-top: 14px;

    font-weight: 600;
    list-style-type: none;

    li {
      display: inline-flex;
      vertical-align: top;
    }

    .elem {
      font-size: 21px;

      padding: 0 7px 9px;
      letter-spacing: 0.9px;
    }

    .active {
      padding-top: 2px;
      border-bottom: 2px solid #e2e1d5;
    }
  }
}


</style>

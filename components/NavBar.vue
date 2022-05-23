<template>
  <div v-bind:class="{active_menu_mobile: menuIsActive}" class="main-block">
    <span class="fa-4x" @click="openMenu();"></span>
    <div class="contain">
      <ul class="social">
        <li><a target="_blank" href="" class="main-image image-1"><p></p></a></li>
        <li><a target="_blank" href="" class="main-image image-2"><p></p></a></li>
        <li><a target="_blank" href="" class="main-image image-3"><p></p></a></li>
        <li><a target="_blank" href="" class="main-image image-4"><p></p></a></li>
      </ul>
      <ul class="nav">
        <li><nuxt-link to="/" class="elem" exact-active-class="active">Home</nuxt-link></li>
        <li><nuxt-link to="/wedding" class="elem" exact-active-class="active">Wedding</nuxt-link></li>
        <li><nuxt-link to="/ceremony" class="elem" exact-active-class="active">Ceremony</nuxt-link></li>
        <li><nuxt-link to="/contact" class="elem" exact-active-class="active">Contact</nuxt-link></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuIsActive: false,
    }
  },
  methods: {
    openMenu() {
      this.menuIsActive = !this.menuIsActive;
    }
}
}
</script>

<style lang="scss" scoped>
.main-block {
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

  @media (min-width: 1100px) and (max-width: 10000px) {

    .contain {
      display: flex;
      flex-direction: row;
      gap: 84px;
      align-items: center;
      padding: 45px 162px 0 0;
      justify-content: flex-end;

      ul {
        margin: 0;
        padding: 0;
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
  }
  @media (min-width: 1100px) and (max-width: 1777.98px) {
    .contain {
      padding: 45px 0 0 0;
      justify-content: center;
    }
  }
  @media (min-width: 200px) and (max-width: 1099.98px) {
    .contain {
      display: flex;
      flex-direction: row-reverse;
      justify-content: space-between;

      li {
        list-style-type: none;
      }

      .social {
        display: flex;
        flex-direction: column;
        gap: 15px;

        margin: 0;
        padding: 0 25px;
      }

      .nav {
        width: 100%;

        margin: 0;
        padding-left: 25px;

        a {
          padding-left: 10px;
        }

        li {
          height: 40px;

          font-size: 25px;

          &:nth-child(1n) {
            border-left: 1px solid #eeeee1;
            border-right: 1px solid #eeeee1;
            border-top: 1px solid #eeeee1;
          }
          &:last-child {
            border-bottom: 1px solid #eeeee1;
          }
        }
      }
    }

    background-color: #dddec3;

    position: fixed;
    top: 0;
    height: 90px;
    width: 100%;
    overflow: hidden;
    transition: 0.3s;

    > span:before {
      content: '\f0c9';
      font-family: 'FontAwesome', serif;
      color: #fdfaf5;
      padding: 0 0 0 20px;
    }

    &.active_menu_mobile {
      height: 285px;
    }
  }

}
</style>

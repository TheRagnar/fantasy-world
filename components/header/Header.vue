<template>
  <header class="header">
    <div class="container">
      <a href="/" class="header__logo">
        <img src="~assets/img/svg/logo.svg" alt="">
      </a>
      <div class="header__control">
        <div class="header__search">
          <HeaderSearch />
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import HeaderSearch from "~/components/header/HeaderSearch.vue";

export default {
  components: {
    HeaderSearch
  }
};
</script>

<style lang="scss">
  @import '~/assets/scss/components/header.scss';
</style>


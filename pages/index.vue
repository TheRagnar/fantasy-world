<template>
  <section class="page">
    <div class="page__header">
      <Header/>
    </div>
      
      <div class="page__content">
        <div class="container">
          <div class="page__grid">
            <div class="page__left-sidebar">
              <div class="page__box">
                Левый сайдбар
              </div>
            </div>
            <div class="page__center">
              <BoockList/>
            </div>
            <div class="page__right-sidebar">
              <div class="page__box">
                Правый сайдбар
              </div>
            </div>
          </div>
        </div>
      </div>
  </section>
</template>

<script>
import Header from '~/components/header/Header.vue'
import BoockList from '~/components/boock/BoockList.vue'

export default {
  components: {
    Header,
    BoockList
  }
}
</script>

<style lang="scss">

</style>


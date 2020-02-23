<template>
    <div class="boock-list">
        <div class="boock-list__flex">
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
            <BoockListItem/>
        </div>
    </div>
</template>

<script>
import BoockListItem from '~/components/boock/BoockListItem.vue'

export default {
  components: {
    BoockListItem
  }
}
</script>

<style lang="scss">
    @import '~/assets/scss/components/boock-list.scss';
</style>
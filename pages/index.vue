<template>
  <div class="container">
    <MainVisualCarousel />
    <PlanCardList />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import MainVisualCarousel from '~/components/organisms/index/IndexMainVisualCarousel.vue'
import PlanCardList from '~/components/organisms/index/IndexPlanCardList.vue'

export default Vue.extend({
  components: {
    MainVisualCarousel,
    PlanCardList
  }
})
</script>

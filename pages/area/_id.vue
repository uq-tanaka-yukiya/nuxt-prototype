<template>
  <div class="container">
    <h1>{{ $route.params.id }} の葬儀場</h1>
    <AreaSearchMap />
    <AreaCardList />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import AreaSearchMap from '~/components/organisms/area/AreaSearchMap'
import AreaCardList from '~/components/organisms/area/AreaCardList'

export default Vue.extend({
  components: {
    AreaSearchMap,
    AreaCardList
  }
})
</script>

<template>
  <section>
    <AreaMap />
    <AreaMapIconLegend />
    <AreaMapSearchForm />
  </section>
</template>

<script lang="ts">
import AreaMap from '../../molecules/area/AreaMap'
import AreaMapIconLegend from '../../molecules/area/AreaMapIconLegend'
import AreaMapSearchForm from '../../molecules/area/AreaMapSearchForm'

export default {
  components: {
    AreaMap,
    AreaMapIconLegend,
    AreaMapSearchForm
  }
}
</script>

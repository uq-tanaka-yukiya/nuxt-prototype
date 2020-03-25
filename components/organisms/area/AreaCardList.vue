<template>
  <section>
    <h2>葬儀場一覧</h2>
    <AreaCard
      v-for="area in areas"
      :key="area.title"
      :title="area.title"
      :address="area.address"
      :tags="area.tags"
    />
  </section>
</template>

<script lang="ts">
import AreaCard from '../../molecules/area/AreaCard'

export default {
  components: {
    AreaCard
  },
  data() {
    return {
      areas: [
        {
          title: 'aaaa',
          address: 'bbbb',
          tags: [
            { title: 'aaaa', disabled: false },
            { title: 'bbbb', disabled: false },
            { title: 'cccc', disabled: false }
          ]
        },
        {
          title: 'aaaa',
          address: 'bbbb',
          tags: [
            { title: 'aaaa', disabled: true },
            { title: 'bbbb', disabled: false },
            { title: 'cccc', disabled: false }
          ]
        },
        {
          title: 'aaaa',
          address: 'bbbb',
          tags: [
            { title: 'aaaa', disabled: false },
            { title: 'bbbb', disabled: true },
            { title: 'cccc', disabled: true }
          ]
        }
      ]
    }
  }
}
</script>

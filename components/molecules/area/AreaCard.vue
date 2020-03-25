<template>
  <div>
    <b-card :title="title">
      <b-card-text>
        {{ address }}
      </b-card-text>
      <b-card-text>
        <FacilityTag
          v-for="tag in tags"
          :key="tag.title"
          :title="tag.title"
          :disabled="tag.disabled"
        />
      </b-card-text>
      <b-link href="#" class="card-link">詳細</b-link>
    </b-card>
  </div>
</template>

<script lang="ts">
import { PropOptions } from 'vue'
import FacilityTag from '../../atoms/area/FacilityTag'
import FacilityTagInterface from '../../../interfaces/plan/FacilityTagInterface'

export default {
  components: {
    FacilityTag
  },
  props: {
    title: { type: String, required: true },
    address: { type: String, required: true },
    tags: { type: Array, required: true } as PropOptions<FacilityTagInterface[]>
  }
}
</script>

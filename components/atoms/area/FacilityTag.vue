<template>
  <b-badge :disabled="disabled" :variant="variant">{{ title }}</b-badge>
</template>

<script lang="ts">
export default {
  props: {
    title: { type: String, required: true },
    disabled: { type: Boolean, default: false }
  },
  computed: {
    variant: (v) => (v.disabled ? 'secondary' : 'primary')
  }
}
</script>

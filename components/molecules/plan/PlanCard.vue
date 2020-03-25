<template>
  <b-card :title="title" :img-alt="title" :img-src="image" overlay />
</template>

<script lang="ts">
export default {
  props: {
    title: { type: String, required: true },
    link: { type: String, required: true },
    image: { type: String, required: true }
  }
}
</script>

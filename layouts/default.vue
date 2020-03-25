<template>
  <div>
    <TheHeader></TheHeader>
    <nuxt />
  </div>
</template>

<script>
import TheHeader from '../components/organisms/layouts/TheHeader'

export default {
  components: {
    TheHeader
  }
}
</script>

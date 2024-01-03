<script setup lang="ts">

</script>

<template lang="pug">
nuxt-layout()
  nuxt-loading-indicator(
    :throttle="0"
    :duration="2000"
    :height="4"
    color="#000"
    )
  nuxt-page()
</template>

<style lang="scss">
.nb {
  border: 1px solid red !important;
}
</style>
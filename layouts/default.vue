<script setup lang="ts">
// name
name: 'default'
</script>
<template lang="pug">
v-app()
  v-main()
    v-container(
      fluid
      class="fill-height"
      )
      v-sheet(
        class="fill-height d-flex justify-center align-center flex-col flex-wrap"
        min-width="100%"
        min-height="100%"
        )
        slot()
    v-divider()
</template>
<style lang="scss"></style>
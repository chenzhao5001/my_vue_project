<template>
  <m-header />
  <tab />
  <router-view />
</template>

<script>
import Header from '@/components/header/header'
import Tab from '@/components/tab/tab'

export default {
  components: {
    MHeader: Header,
    Tab
  },
  computed: {}
}

</script>

<style lang="scss">
#app {
}
</style>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <AppHeader />

  <AppMain />

  <AppFooter />
</template>

<style lang="scss" scoped>
@use './style/generals.scss' as *;
@use './style/partials/variables' as *;
@use './style/partials/reset' as *;
</style>

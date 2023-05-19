<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import TheBlue from './components/TheBlue.vue'
import TheOptions from './components/TheOptions.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components:{
    AppHeader,
    AppMain,
    TheBlue,
    TheOptions,
    AppFooter
  }
}
</script>

<template>
  <div class="container">
    <AppHeader />
    <AppMain />
    <TheBlue />
    <TheOptions />
    <AppFooter />
  </div>
</template>

<style scoped>

</style>

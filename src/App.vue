<template>
  <div>
    <AppTitleComponent />
    <AppHeroComponent />
  </div>
</template>

<script>
  import AppTitleComponent from './components/AppTitleComponent.vue'
  import AppHeroComponent from './components/AppHeroComponent.vue'
  export default {
    name:'App',
    components: {
      AppTitleComponent,
      AppHeroComponent
    },
    data() {
      return {
        
      }
    },
  }
</script>

<style lang="scss" scoped>

</style>
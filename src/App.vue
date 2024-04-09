<template>
  <AppTitleComponent/>
  <AppHeroComponent/>
</template>

<script>
  import AppTitleComponent from './components/AppTitleComponent.vue';
  import AppHeroComponent from './components/AppHeroComponent.vue';
  export default {
    name: 'App',
    components: {
      AppTitleComponent,
      AppHeroComponent
    },
    data(){
      return {
        
      }
    },
    methods: {

    }
  }
</script>

<style scoped>
    
</style>
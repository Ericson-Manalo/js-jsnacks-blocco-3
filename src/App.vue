<script>
  import AppHeader from './components/AppHeader.vue';

  export default{
    name: 'AppHeader',
    components:{
      AppHeader,
    }
  }
</script>

<template>
  <AppHeader/>
  <NavLink/>
</template>

<style lang="scss">
  @import './styles/general.scss';
</style>

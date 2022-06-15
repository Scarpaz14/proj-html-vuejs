<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/blocks/HeaderComponent.vue';
import MainComponent from './components/blocks/MainComponent.vue';
import FooterComponent from './components/blocks/FooterComponent.vue';


export default {
  name: 'App',
  components:{
    HeaderComponent,
    MainComponent,
    FooterComponent
}
 
}
</script>

<style lang="scss">
@import './assets/style/global.scss';

</style>

<template>
  <main>
    <HeroSectionVue/>
    <StatisticsSectionVue/>

  </main>
</template>

<script>
import HeroSectionVue from '../sections/HeroSection.vue'
import StatisticsSectionVue from '../sections/StatisticsSection.vue'
export default {
    name:'MainComponent',
    components:{
    HeroSectionVue,
    StatisticsSectionVue
}
}
</script>

<style>

</style>
<template>
  <main>
    <HeroSectionVue/>
    <StatisticsSectionVue/>
    <WorkSectionVue/>

  </main>
</template>

<script>
import HeroSectionVue from '../sections/HeroSection.vue'
import StatisticsSectionVue from '../sections/StatisticsSection.vue'
import WorkSectionVue from '../sections/WorkSection.vue'
export default {
    name:'MainComponent',
    components:{
    HeroSectionVue,
    StatisticsSectionVue,
    WorkSectionVue
}
}
</script>

<style>

</style>
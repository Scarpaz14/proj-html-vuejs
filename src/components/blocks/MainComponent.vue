<template>
  <main>
    <HeroSectionVue/>
    <StatisticsSectionVue/>
    <WorkSectionVue/>
    <CoursesSectionVue/>

  </main>
</template>

<script>
import HeroSectionVue from '../sections/HeroSection.vue'
import StatisticsSectionVue from '../sections/StatisticsSection.vue'
import WorkSectionVue from '../sections/WorkSection.vue'
import CoursesSectionVue from '../sections/CoursesSection.vue'
export default {
    name:'MainComponent',
    components:{
    HeroSectionVue,
    StatisticsSectionVue,
    WorkSectionVue,
    CoursesSectionVue
}
}
</script>

<style>

</style>
<template>
  <main>
    <HeroSectionVue/>
    <StatisticsSectionVue/>
    <WorkSectionVue/>
    <CoursesSectionVue/>
    <TalkAboutSectionVue/>
    <LastWorkSectionVue/>
    <HelpersSectionVue/>

  </main>
</template>

<script>
import HeroSectionVue from '../sections/HeroSection.vue'
import StatisticsSectionVue from '../sections/StatisticsSection.vue'
import WorkSectionVue from '../sections/WorkSection.vue'
import CoursesSectionVue from '../sections/CoursesSection.vue'
import TalkAboutSectionVue from '../sections/TalkAboutSection.vue'
import LastWorkSectionVue from '../sections/LastWorkSection.vue'
import HelpersSectionVue from '../sections/HelpersSection.vue'
export default {
    name:'MainComponent',
    components:{
    HeroSectionVue,
    StatisticsSectionVue,
    WorkSectionVue,
    CoursesSectionVue,
    TalkAboutSectionVue,
    LastWorkSectionVue,
    HelpersSectionVue,
    
}
}
</script>

<style lang="scss" scoped>

</style>
<template>
  <main>
    <HeroSectionVue/>
    <StatisticsSectionVue/>
    <WorkSectionVue/>
    <CoursesSectionVue/>
    <TalkAboutSectionVue/>

  </main>
</template>

<script>
import HeroSectionVue from '../sections/HeroSection.vue'
import StatisticsSectionVue from '../sections/StatisticsSection.vue'
import WorkSectionVue from '../sections/WorkSection.vue'
import CoursesSectionVue from '../sections/CoursesSection.vue'
import TalkAboutSectionVue from '../sections/TalkAboutSection.vue'
export default {
    name:'MainComponent',
    components:{
    HeroSectionVue,
    StatisticsSectionVue,
    WorkSectionVue,
    CoursesSectionVue,
    TalkAboutSectionVue
}
}
</script>

<style lang="scss" scoped>

</style>
<template>
  <footer>
    <FooterHeroSection/>
    <StarterNowFooterSections/>

  </footer>
</template>

<script>
import FooterHeroSection from '../sections/FooterHeroSection'
import StarterNowFooterSections from '../sections/StarterNowFooterSections.vue'
 
export default {
    name: 'FooterComponent',
    components:{
        FooterHeroSection,
        StarterNowFooterSections

    }
    

}
</script>

<style lang="scss" scoped>

</style>
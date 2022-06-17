<template>
    <section id="started-now">
        <div class="container">
            <div class="row text-center">
                <div class="col">
                    <h3>Start today for getting <mark>Online Certification</mark></h3>
                    <h2>You can be yuor own guiding star with our help!</h2>
                    <div class="btn_general pt-4">
                        <button class="btn-all">Get started for free</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'StarterNowFooterSections'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';

#started-now{
    margin: 80px 0;
}
.btn-all{
    @include btn-general
}
mark{
  @include markColor;
}


</style>
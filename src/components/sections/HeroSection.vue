<template>
    <section id="hero">
        <div class="container">
            <div class="hero-paragrafh text-center text-white py-4">
                <div class="title">
                    <h1>Learn At Your Own Pace!</h1>
                    <p class="my-4">Get teamed up with people of the same will.</p>
                </div>
                <div class="btn_general">
                    <button class="btn-all">Get started for free</button>
                </div>
            </div>
        </div>
        <div class="hero-image">
            <img class="img" src="../../assets/image/hero-image.png" alt="">
        </div>
    </section>
</template>

<script>
export default {
    name:"HeroSection"

}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';

section{
    background-color: #1f1f52;
}
.title{
    margin-top: 70px;
}
.img{
    object-fit: cover;
    margin: auto;
    width: 100%;
}
.btn-all{
    @include btn-general
}

.btn-all:hover{
    @include hoverBtnWhite
    
}



</style>
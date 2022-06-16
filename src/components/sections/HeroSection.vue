<template>
    <section id="hero">
        <div class="container">
            <div class="hero-paragrafh text-center text-white py-4">
                <div class="title">
                    <h1>Learn At Your Own Pace!</h1>
                    <p>Get teamed up with people of the same will.</p>
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
    padding: 10px 25px;
    border-radius: 5px;
    background: #20ad96;
    border: none;
    color:white
}



</style>
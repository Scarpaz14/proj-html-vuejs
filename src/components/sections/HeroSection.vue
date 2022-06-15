<template>
    <section>
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
            <div class="row">
                <div class="col d-flex justify-content-center">
                    <img class="left  p-4" src="../../assets/image/home-6-hero-left-person.png" alt="">
                    <img class="center bg-white p-3" src="../../assets/image/home-6-hero-poster-final.jpg" alt="">
                    <img class="right d-flex align-self-end  p-4" src="../../assets/image/home-6-hero-right-person-195x300.png" alt="">
                </div>
                
            </div>
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
    padding: 20px 0;
}
.left{
    width:30%;
    position: relative;
    right: -20px;
}

.center{
    width: 50%;
    position: relative;
    left: -70px;
    border-radius: 30px;
}

.right{
    position: relative;
    left: -90px;
    top:170px
}

.row{
    max-width: 100%;
    position: relative;
    top: 80px;
    overflow: hidden;
}

.btn-all{
    padding: 10px 25px;
    border-radius: 5px;
    background: #20ad96;
    border: none;
    color:white
}



</style>
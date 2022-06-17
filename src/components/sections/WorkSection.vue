<template>
  <section id="work">
    <div class="container d-flex">
        <div class="row">
            <div class="col-xs-12 col-sm-12 col-md-12 col-lg-10">
                <div class="descpition mx-4">
                    <h4>Graphic Design</h4>
                    <p>Have a passion for graphics and arts? Show your talents with confidence and self-asserivensess.</p>
                    <img src="../../assets/image/home-6-service-image-01.png" alt="">
                </div>
            </div>
            <div class="col-xs-12 col-sm-12 col-md-12 col-lg-10">
                <div class="descpition mx-4">
                    <img src="../../assets/image/home-6-service-image-03.png" alt="">
                    <h4>Idea Discussion</h4>
                    <p>Get teamed up with the specialist who work and teach coding for years at famous universities.</p>
                </div>
            </div>
        </div>
        <div class="row">
             <div class="col-xs-12 col-sm-12 col-md-12 col-lg-10">
                <div class="descpition my-5 mx-4">
                    <h4>Business Administration</h4>
                    <p>Learners are encouraged to study the mechanism and structure of system administration.</p>
                    <img src="../../assets/image/home-6-service-image-02.png" alt="">
                </div>
            </div>
            <div class="col-xs-12 col-sm-12 col-md-12 col-lg-10">
                <div class="descpition mx-4">
                    <img src="../../assets/image/home-6-service-image-04.png" alt="">
                    <h4>Web Development</h4>
                    <p>Learn to start building a webpage from scratch. You decide your own pace, course and speed</p>
                </div>
            </div>
        </div>
        <div class="row d-flex align-items-center">
            <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
                <div class="service">
                    <p>TOGHETER WE CAN CREATE</p>
                    <h1 class="mb-5">Services We <mark>Can Provide</mark> for my Clientss</h1>
                </div>
                <ul class="service-list">
                    <li>
                      <p><i class="fa-solid fa-check"></i>Select & Customize to yuor preferences</p>
                    </li>
                    <li>
                      <p><i class="fa-solid fa-check"></i>Change the tutor and make arrangements</p>
                    </li>
                    <li>
                      <p><i class="fa-solid fa-check"></i>Partecipate in events to join others</p>
                    </li>
                    <li>
                      <p><i class="fa-solid fa-check"></i>Get the desidered certificate deliverd at house</p>
                    </li>
                </ul>
                <div class="btn_general">
                    <button class="btn-all">Get started for free</button>
                </div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name:'WorkSection'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';

h4{
    margin: 15px 0;
}

mark{
    @include markColor
}
.descpition{
    padding: 20px;
    box-shadow: 10px 5px 5px lightgray;
}
.row{
    width: 50%;  
}
.service-list{
    list-style: none;
    padding: 0;
    li{
        display: flex;
        align-items: center;
    }
    .fa-check{
        margin-right: 10px;
        color:var(--primary-color);
    }
}
.btn-all{
    @include btn-general
}

.btn-all:hover{
    @include hoverBtnPurple
}
</style>
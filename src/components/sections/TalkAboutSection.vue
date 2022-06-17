<template>
    <section>
        <div class="container">
            <div class="row text-center">
                <div class="col">
                    <h1>Why People Talk About<mark>MaxCoach</mark>?</h1>
                </div>
            </div>
            <div class="row d-flex justify-content-center align-items-center">
                <div class="col-3">
                    <img class="course-img img-fluid" src="../../assets/image/person-talk-about.png" alt="">
                </div>
                <div class="col-6">
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Id corporis magnam, suscipit quod facere natus porro eos ducimus! Animi quis quam quisquam cumque quas quia labore sequi in quos eius.</p>
                    <p>MINA HOLLACE</p>
                    <small>/Frelancer</small>
               </div>
            </div>
            <div class="row images-client text-center my-5">
                <div class="col-2" v-for="(client,index) in clients" :key="index">
                    <img :src="client.image" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'TalkAboutSection',
    data(){
        return{
            clients: [
                {   
                    image: require("../../assets/image/client-logo-colored-01.png"),
                },
                {
                    image: require("../../assets/image/client-logo-colored-02.png"),
                },
                {
                    image: require("../../assets/image/client-logo-colored-03.png"),
                },
                {
                    image: require("../../assets/image/client-logo-colored-04.png"),
        
                },
                {
                    image: require("../../assets/image/client-logo-colored-05.png"),
                },
              
                {
                    image: require("../../assets/image/client-logo-colored-06.png"),
                   
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';
.images-client{
    .col-2{
        display: flex;
        align-items: center;
        justify-content: center;
    }
}
mark{
  @include markColor;
}
.course-img{
    width: 280px;
    height: 280px;
    border-radius: 50%;
}

</style>
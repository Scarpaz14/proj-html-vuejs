<template>
    <section>
        <div class="container">
            <div class="row text-center mb-5">
                <div class="col-12">
                    <h1>Why People Talk About<mark>MaxCoach</mark>?</h1>
                </div>
            </div>
            <div class="row d-flex justify-content-center align-items-center">
                <div class="col-xs-12 col-sm-12 col-md-3 col-lg-3">
                    <img class="course-img img-fluid" src="../../assets/image/person-talk-about.png" alt="">
                </div>
                <div class="col-6">
                    <h4>I am free to learn at my own pace, follow my own schedule and choose the subject I like. Great study portal for people like me.</h4>
                    <p class="fw-bold my-4">MINA HOLLACE</p>
                    <span class="work">/Frelancer</span>
               </div>
            </div>
            <div class="row images-client text-center my-5">
                <div class="col-xs-12 col-sm-12 col-md-6 col-lg-2" v-for="(client,index) in clients" :key="index">
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
    display: flex;
    align-items: center;
    justify-content: center;
}
mark{
  @include markColor;
}

.work{
    color:grey;
}
.course-img{
    width: 280px;
    height: 280px;
    border-radius: 50%;
}

</style>
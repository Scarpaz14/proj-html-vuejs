<template>
    <section id="helpers">
        <div class="container">
            <div class="row text-center mb-5">
                <div class="col">
                    <p>WANNA TRANFORM YOUR LIFE?</p>
                    <h1 class="mb-5">Glad to<mark>Help You</mark>Learn</h1>
                </div>
            </div>
            <div class="row mb-5">
                <div class="col-3" v-for="(icon,index) in icons" :key="index">
                    <img :src="icon.icon" alt="">
                    <h4>{{icon.title}}</h4>
                    <p class="text">{{icon.text}}</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'HelpersSection',
    data(){
        return{
           
            icons: [
                {
                    icon:"https://maxcoach.thememove.com/wp-content/uploads/2020/03/landing-feature-ux-design.png",
                    title: "Idea Discussion",
                    text:"Get teamed up with the specilists who work and tech coding for years at famous universities"
                },
                {
                    icon:"https://maxcoach.thememove.com/wp-content/uploads/2020/03/landing-feature-widely-compatible.png",
                    title: "Web Development",
                    text: "Learn to start building a awebpage from scratch. You decide youtnown pace, course and speed",
                },
                {
                    icon:"https://maxcoach.thememove.com/wp-content/uploads/2020/03/landing-feature-awesome-font.png",
                    title: "System Administration",
                    text: "Learners are encouraged to study the mechanism and structure of the system administration",
                },
                {
                    icon:"https://maxcoach.thememove.com/wp-content/uploads/2020/03/landing-feature-breadcrumbs-available-.png",
                    title: "Graphic Design",
                    text: "Have a passion for graphics and arts? Show your talents with confidence and self-asseriveness",
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';
mark{
  @include markColor;
}

#helpers{
    padding: 70px 0;
}
h4{
    margin: 20px 0;
}

.fa-gear,.fa-flag,.fa-life-ring,.fa-tv{
    font-size: 60px;
}

.text{
    color:grey
}

</style>
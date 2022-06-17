<template>
    <section id="courses">
        <div class="container">
            <div class="row text-center">
                <div class="col-12">
                    <h5>CHOOSE A COURSE TO GET STARTED</h5>
                    <h1>Latest Featured<mark>Courses</mark></h1>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6" v-for="(course,index) in courses" :key="index">
                    <div class="course-type d-flex">
                        <img class="course-img img-fluid" :src="course.image" alt="">
                        <div class="info">
                            <mark class="price fw-bold p-0">{{course.price}}</mark>
                            <p class="fw-bold my-2">{{course.typo}}</p>
                            <span><small><i class="fa-regular fa-file"></i>{{course.lesson}}</small> <small><i class="fa-regular fa-user"></i>{{course.students}}</small></span>
                        </div>
                    </div>
                </div>
                <div class="row text-center my-5">
                    <div class="col">
                        <div class="btn_general">
                            <button class="btn-all">Wiew all courses <i class="fa-solid fa-arrow-right"></i></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name:'CoursesSection',
    data(){
        return{
           
            courses: [
                {   
                    image: require("../../assets/image/course-02-480x298.jpg"),
                    price:"$40.00",
                    typo: "Learing to write as a professional Author",
                    lesson: "20 lesson",
                    students: "50 students"
                },
                {
                    image: require("../../assets/image/stock-full-hd-04-480x298.jpg"),
                    price:"$19.00",
                    typo: "Open Programmming Courses for Everyone:Python",
                    lesson:"30 lesson",
                    students: "62 students"
                },
                {
                    image: require("../../assets/image/course-featured-image-01-480x298.jpg"),
                    price:"$39.00",
                    typo: "Master jQuery in a Short Period of time",
                    lesson:"10 lesson",
                    students:"30 students"
                },
                {
                    image: require("../../assets/image/stock-full-hd-03-480x298.jpg"),
                    price:"Free",
                    typo: "Customer-centric Info-Tech Strategies",
                    lesson:"18 lesson",
                    students: "547 students"
                },
                {
                    image: require("../../assets/image/stock-full-hd-06-480x298.jpg"),
                    price:"$26.00",
                    typo: "Academic Listening and Note-taking",
                    lesson:"24 lesson",
                    students: "800 studnets"
                },
                {
                    image: require("../../assets/image/stock-full-hd-05-480x298.jpg"),
                    price:"$59.00",
                    typo: "Introduction to Javascript for Beginners",
                    lesson:"14 lesson",
                    students:"80 students"
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';

small{
    margin-right: 10px;
    .fa-file,.fa-user{
    margin-right: 5px;
    }
}

.course-type{
    transition: 1s;
}
.course-type:hover{
    @include hoverCard
}
#courses{
    margin: 100px 0;
    background-color: #f5f7fa;
}
.price{
    @include markColor;
    font-size: 1.5625rem;
}
mark{
  @include markColor;
}

h5,h1{
    margin: 50px 0;
}

.info{
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.course-img{
    margin: 30px;
    display: inline-block;
    width: 150px;
    height: 150px;
    line-height: 150px;
    object-fit: cover;
    border-radius: 50%;
    box-shadow: 10px 5px 5px lightgray;
}


.btn-all{
    @include btn-general
}

.btn-all:hover{
    @include hoverBtnPurple
}
</style>
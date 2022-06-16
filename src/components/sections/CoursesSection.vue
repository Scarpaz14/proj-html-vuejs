<template>
    <section id="courses">
        <div class="container">
            <div class="row text-center">
                <div class="col">
                    <h5>CHOOSE A COURSE TO GET STARTED</h5>
                    <h1>Latest FEATURED Courses</h1>
                </div>
            </div>
            <div class="row">
                <div class="col-6">
                    <div class="course-type d-flex">
                        <img class="course-img img-fluid" src="../../assets/image/course-02-480x298.jpg" alt="">
                        <div class="info">
                            <p class="price">$40.00</p>
                            <p>Learing to write as a professional author</p>
                            <span>20 Lesson <span>50 studenti</span></span>
                        </div>
                    </div>
                </div>
                 <div class="col-6">
                    <div class="course-type d-flex">
                        <img class="course-img img-fluid" src="../../assets/image/course-02-480x298.jpg" alt="">
                        <div class="info">
                            <p class="price">$40.00</p>
                            <p>Learing to write as a professional author</p>
                            <span>20 Lesson <span>50 studenti</span></span>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="course-type d-flex">
                        <img class="course-img img-fluid" src="../../assets/image/course-02-480x298.jpg" alt="">
                        <div class="info">
                            <p class="price">$40.00</p>
                            <p>Learing to write as a professional author</p>
                            <span>20 Lesson <span>50 studenti</span></span>
                        </div>
                    </div>
                </div>
                 <div class="col-6">
                    <div class="course-type d-flex ">
                        <img class="course-img img-fluid" src="../../assets/image/course-02-480x298.jpg" alt="">
                        <div class="info">
                            <p class="price">$40.00</p>
                            <p>Learing to write as a professional author</p>
                            <span>20 Lesson <span>50 studenti</span></span>
                        </div>
                    </div>
                </div>
                 <div class="col-6">
                    <div class="course-type d-flex ">
                        <img class="course-img img-fluid" src="../../assets/image/course-02-480x298.jpg" alt="">
                        <div class="info">
                            <p class="price">$40.00</p>
                            <p>Learing to write as a professional author</p>
                            <span>20 Lesson <span>50 studenti</span></span>
                        </div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="course-type d-flex">
                        <img class="course-img img-fluid" src="../../assets/image/course-02-480x298.jpg" alt="">
                        <div class="info">
                            <p class="price">$40.00</p>
                            <p>Learing to write as a professional author</p>
                            <span>20 Lesson <span>50 studenti</span></span>
                        </div>
                    </div>
                </div>
                <div class="row text-center my-5">
                    <div class="col">
                        <div class="btn_general">
                            <button class="btn-all">Wiew all courses --></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name:'CoursesSection'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';
#courses{
    margin: 200px 0;
    background-color: #f5f7fa;
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
}
.btn-all{
    @include btn-general
}
</style>
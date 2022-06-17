<template>
    <section id="last-work">
        <div class="container">
            <div class="row text-center mb-5">
                <div class="col">
                    <p>EJOY READING ON MAXCOACH</p>
                    <h1>Latest on<mark>Our Blogs</mark></h1>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4" v-for="(worker,index) in works" :key="index">
                     <img class="img-fluid" :src='worker.image' alt="">
                     <h6 class="worker mt-4">{{worker.work}}</h6>
                     <h4>{{worker.info}}</h4>
                     <span class="info"><small><i class="fa-regular fa-calendar"></i>{{worker.date}}</small> <small><i class="fa-regular fa-eye"></i>{{worker.wiews}}</small></span>
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'LastWorkSection',
       data(){
        return{
            works: [
                {   
                    image: require("../../assets/image/artist-blog-03-480x325.jpeg"),
                    work:"ARTIST",
                    info: "Brush Strokes Energize Trees in Paintings",
                    date: "May 15,2020",
                    wiews: "687 wiews"
                },
                {
                    image: require("../../assets/image/artist-blog-01-480x325.jpg"),
                    work:"ARTIST",
                    info: "Pocket-Sized Notebooks Hold Miniature Paintings",
                    date:"May 15,2020",
                    wiews: "602 wiews"
                },
                {
                    image: require("../../assets/image/artist-blog-02-480x325.jpg"),
                    work:"ARTIST",
                    info: "Connection Between Self-Portaits Identity",
                    date:"May 15,2020",
                    wiews:"390 wiews"
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';

#last-work{
    background-color: #f5f7fa;
    padding: 100px 0;
}
mark{
    @include markColor
}
 .img-fluid{
        border-radius: 10px;
}

.worker, .info{
    color:grey
}

small{
    margin-right: 10px;
    .fa-calendar,.fa-eye{
    margin-right: 5px;
    }
}

</style>
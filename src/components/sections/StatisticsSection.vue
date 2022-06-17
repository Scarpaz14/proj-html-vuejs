<template>
    <section id="statistics">
        <div class="container">
            <div class="row d-flex justify-content-center text-center">
                <div class="col-6 col-lg-6">
                    <div class="section-title mb-5">
                        <h3>Let passion and determination be the guide along the way and develop at your own pace that's confortable</h3>
                        <p class="name fw-bold mt-5">FANNIE MORENO</p>
                        <small id="founder">/Founder & CEO</small>
                    </div>
                </div>
            </div>
            <div class="number-statistics row d-flex justify-content-center text-center my-5">
                <div class="col-xs-12 col-sm-6 col-lg-3" v-for="(number,index) in numbers" :key="index">
                    <p>{{number.number}}</p>
                    <p>{{number.typo}}</p>
                </div>
            </div>
        </div>
        
    </section>
</template>

<script>
export default {
    name:'StatisticsSection',
    data(){
        return{
           
            numbers: [
                {
                    number:"1.926",
                    typo: "finished lesson",
                },
                {
                    number:"3.092+",
                    typo: "enrolled learners",
                },
                {
                    number:"200",
                    typo: "online instructors",
                },
                {
                    number:"100%",
                    typo: "satisfaction rate",
                },
            ],
        }
    }
}

</script>

<style lang="scss" scoped>

#statistics{
    margin: 150px 0;
}

.number-statistics{
    p:first-child{
        font-size: 35px;
        color:var(--primary-color);
        font-weight: bold;
    }
    
    p:last-child{
        text-transform: uppercase;
    }
}

#founder{
    color:grey
}
</style>
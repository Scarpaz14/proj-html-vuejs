<template>
  <section id="work">
    <div class="container d-flex">
        <div class="row">
            <div class="col-10">
                <div class="descpition mx-4">
                    <h4>Graphic Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error, ut dolor, dignissimos ipsam tempore nostrum quaerat, quasi consectetur impedit dolorum est alias commodi temporibus doloribus necessitatibus quam exercitationem amet iure.</p>
                    <img src="../../assets/image/home-6-service-image-01.png" alt="">
                </div>
            </div>
            <div class="col-10">
                <div class="descpition mx-4">
                    <img src="../../assets/image/home-6-service-image-03.png" alt="">
                    <h4>Graphic Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error, ut dolor, dignissimos ipsam tempore nostrum quaerat, quasi consectetur impedit dolorum est alias commodi temporibus doloribus necessitatibus quam exercitationem amet iure.</p>
                </div>
            </div>
        </div>
        <div class="row">
             <div class="col-10">
                <div class="descpition my-5 mx-4">
                    <h4>Graphic Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error, ut dolor, dignissimos ipsam tempore nostrum quaerat, quasi consectetur impedit dolorum est alias commodi temporibus doloribus necessitatibus quam exercitationem amet iure.</p>
                    <img src="../../assets/image/home-6-service-image-02.png" alt="">
                </div>
            </div>
            <div class="col-10">
                <div class="descpition mx-4">
                    <img src="../../assets/image/home-6-service-image-04.png" alt="">
                    <h4>Graphic Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error, ut dolor, dignissimos ipsam tempore nostrum quaerat, quasi consectetur impedit dolorum est alias commodi temporibus doloribus necessitatibus quam exercitationem amet iure.</p>
                </div>
            </div>
        </div>
        <div class="row d-flex align-items-center">
            <div class="col-10">
                <div class="service">
                    <p>TOGHETER WE CAN CREATE</p>
                    <h1>Services We Can Provide for my Clientss</h1>
                </div>
                <ul class="service-list">
                    <li>
                      <p><i class="fa-solid fa-check"></i>Select & Customize to yuor preferences</p>
                    </li>
                    <li>
                      <p><i class="fa-solid fa-check"></i>Select & Customize to yuor preferences</p>
                    </li>
                    <li>
                      <p><i class="fa-solid fa-check"></i>Select & Customize to yuor preferences</p>
                    </li>
                    <li>
                      <p><i class="fa-solid fa-check"></i>Select & Customize to yuor preferences</p>
                    </li>
                </ul>
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


.descpition{
    border: 2px solid black;
    padding: 20px;
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
    }
}
</style>
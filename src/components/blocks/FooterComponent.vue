<template>
  <footer>
    <FooterHeroSection/>
    <StarterNowFooterSection/>
    <div class="footer-bottom py-5">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <h4>Addres</h4>
                    <p>382 NE 191st St #87394 Miami, FL 33179-3899</p>
                    <p>+1(305) 547-90909(9am - 5pm EST, Monday-Friday)</p>
                    <p>support@maxcoach.com</p>
                    <div class="social"><i class="fa-brands fa-facebook-square"></i><i class="fa-brands fa-twitter mx-4"></i><i class="fa-brands fa-instagram"></i><i class="fa-brands fa-linkedin mx-4"></i></div>
                </div>
                 <div class="col-2">
                    <h4>Explore</h4>
                    <ul>
                        <li><a href="#">Start here</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">About us</a></li>
                    </ul>
                </div>
                 <div class="col-2 pt-4 mt-2">
                    <ul>
                        <li><a href="#">Succes story</a></li>
                        <li><a href="#">Courses</a></li>
                        <li><a href="#">Contact us</a></li>
                    </ul>
                </div>
                 <div class="col-2">
                     <h4>Information</h4>
                    <ul>
                        <li><a href="#">Membership</a></li>
                        <li><a href="#">Purchase guide</a></li>
                        <li><a href="#">Privacy policy</a></li>
                        <li><a href="#">Terms of services</a></li>
                    </ul>
                </div>
            </div>
            <div class="row d-flex align-items-center text-center mt-5">
                <div class="col">
                    <h6>2020 MaxCoach. All Rights Reserved</h6>
                </div>
            </div>
        </div>

    </div>

  </footer>
</template>

<script>
import FooterHeroSection from '../sections/FooterHeroSection'
import StarterNowFooterSection from '../sections/StarterNowFooterSection.vue'
 
export default {
    name: 'FooterComponent',
    components:{
        FooterHeroSection,
        StarterNowFooterSection

    }
}
</script>

<style lang="scss" scoped>

.footer-bottom{
    background-color: #f8f8f8;
    li{
        list-style: none;
    }
    a{
        text-decoration: none;
        color:grey
    }

    ul{
        padding: 0;
    }
}
.social{
    font-size:40px;
    color:grey
}
p,h6{
    color:grey
}
    

</style>
<template>
  <footer>
    <FooterHeroSection/>
    <StarterNowFooterSection/>
    <div class="footer-bottom py-5">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <h4>Addres</h4>
                    <small>382 NE 191st St #87394 Miami, FL 33179-3899</small>
                    <small>+1(305) 547-90909(9am - 5pm EST, Monday-Friday)</small>\
                    <small>support@maxcoach.com</small>
                    <div class="social"><i class="fa-brands fa-facebook-square"></i><i class="fa-brands fa-twitter mx-4"></i><i class="fa-brands fa-instagram"></i><i class="fa-brands fa-linkedin mx-4"></i></div>
                </div>
                 <div class="col-2">
                    <h4>Addres</h4>
                    <ul>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                    </ul>
                </div>
                 <div class="col-2">
                     <h4>Addres</h4>
                    <ul>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                    </ul>
                </div>
                 <div class="col-2">
                     <h4>Addres</h4>
                    <ul>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                    </ul>
                </div>
            </div>
            <div class="row d-flex align-items-center text-center mt-5">
                <div class="col">
                    <h7>2020 MaxCoach. All Rights Reserved</h7>
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
        color:inherit
    }
}

.social{
    font-size:40px;
    color:grey
}
    

</style>
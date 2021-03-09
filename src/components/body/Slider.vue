<template>
  <div class="slider pb-5" id="portfolio">
      <div class="container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-12">

                    <div class="row">
                        <div class="col-md-12">
                            <div class="head">
                                <span class="heading">Our</span>
                                Works
                            </div>
                        </div>
                    </div>

                    <div class="row mt-3 mb-5">
                        <div class="col-md-12">
                            <div class="sub-head">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>
                                Lorem ipsum dolor sit amet consectetur adipisicing elit adipisicing elit.
                            </div>
                        </div>
                    </div>

<!-- slider -->
                    <splide :options="options">
                        <splide-slide>
                            <div class="card">
                                <img class="img-fluid" alt="100%x280" src="./../../assets/header/body/portfolio-pic5.jpg">
                                <div class="card-body">
                                    <h4 class="card-title">Hipster</h4>
                                    <p class="card-text">Web Design</p>
                                    <p class="card-date">18.10.2019</p>
                                </div>
                                
                                <a class="open" href="">
                                    <i class="far fa-share-square"></i>
                                </a>
                            </div>
                        </splide-slide>

                       <splide-slide>
                            <div class="card">
                                <img class="img-fluid" alt="100%x280" src="./../../assets/header/body/portfolio-pic5.jpg">
                                <div class="card-body">
                                    <h4 class="card-title">Hipster</h4>
                                    <p class="card-text">Web Design</p>
                                    <p class="card-date">18.10.2019</p>
                                </div>
                                
                                <a class="open" href="">
                                    <i class="far fa-share-square"></i>
                                </a>
                            </div>
                        </splide-slide>

                        <splide-slide>
                            <div class="card">
                                <img class="img-fluid" alt="100%x280" src="./../../assets/header/body/portfolio-pic5.jpg">
                                <div class="card-body">
                                    <h4 class="card-title">Hipster</h4>
                                    <p class="card-text">Web Design</p>
                                    <p class="card-date">18.10.2019</p>
                                </div>
                                
                                <a class="open" href="">
                                    <i class="far fa-share-square"></i>
                                </a>
                            </div>
                        </splide-slide>

                        <splide-slide>
                            <div class="card">
                                <img class="img-fluid" alt="100%x280" src="./../../assets/header/body/portfolio-pic5.jpg">
                                <div class="card-body">
                                    <h4 class="card-title">Hipster</h4>
                                    <p class="card-text">Web Design</p>
                                    <p class="card-date">18.10.2019</p>
                                </div>
                                
                                <a class="open" href="">
                                    <i class="far fa-share-square"></i>
                                </a>
                            </div>
                        </splide-slide>
                    </splide>
<!-- slider -->

                </div>
            </div>
        </div> 
      </div>
  </div>
</template>



<script>
import { Splide, SplideSlide } from '@splidejs/vue-splide';

export default {
  components: {
    Splide,
    SplideSlide,
  },

  name: 'Slider',

  data () {
    return {
        options: {
            perPage: 3,
            rewind: true,
            type: 'loop',
            autoplay: true,
            gap: '1rem',
            pagination : false
        },
    }
  },

  methods: {
      next () {
        
      }
  }
}
</script>

<style scoped> 
  .head{
      text-align: center;
      font-size: 30px;
      font-weight: bold;
      font-family: Montserrat;
  }
  .heading{
      padding: 15px;
      background-image: url("./../../assets/header/body/path-15.png");
      background-repeat: no-repeat;
  }
 .sub-head{
     text-align: center;
     font-family: "Montserrat";
     font-size: 16px;
     color: rgb(132, 132, 132);
 }
 /* slider */
 .slider-buttons{
     height: 50px;
     width: 50px;
     border-radius: 100%;
     position: absolute;
     background-color: transparent;
     bottom: 200px;
     color: rgb(132, 132, 132) !important;
 }
 i{
    font-size: 32px;
    display: flex;
    justify-content: center;
    align-items: center;
 }
 .card{
     margin: 25px 0;
     box-shadow: 0px 10px 19px rgba(0, 0, 0, 0.1);
     border-radius: 3px;
 }
 .card-title{
     text-align: center;
     font-family: "Montserrat";
     font-size: 26px;
 }
 .card-text{
     text-align: center;
     font-family: "Montserrat";
     font-size: 16px;
     color: rgb(132, 132, 132);
 }
 .card-date{
     text-align: left;
     margin: 50px 0 0 0;
     font-size: 12px;
     color: rgb(132, 132, 132);
     font-family: "Montserrat";
 }
 .moved{
     transform: perspective(500px) translateY(-20px);
 }
 .open{
     display: flex;
     justify-content: center;
     align-items: center;
     right: 35px;
     bottom: -25px;
     position: absolute;
     border-radius: 100%;
     box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.11);
     height: 48px;
     cursor: pointer;
     width: 48px;
     background-color: rgba(0255, 255, 255, 1);
     color: rgba(237, 110, 0, 1);
 }

 /* media */
  @media only screen and (max-width: 580px) {
    #portfolio{
        display: none;
    }
 }
</style>
    
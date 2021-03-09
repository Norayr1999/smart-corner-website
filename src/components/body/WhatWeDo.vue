<template>
  <div class="WhatWeDo" id="services">
      <div class="container-fluid">
        <div class="container">

            <div class="row">
                <!-- left col -->
                <div class="col-md-7">
                    <div class="row">
                        <div class="col-md-4 par">
                            <div class="sub-divs-1">
                                <img src="./../../assets/header/body/programmer.svg" class="img-fluid mt-4">
                                <p class="mt-4 desc">BRANDING <br> IDENTITY</p>
                            </div>
                        </div>

                        <div class="col-md-4 middle-parent">
                            <div class="sub-divs-2 left mb-5">
                                <img src="./../../assets/header/body/ui-design.svg" class="img-fluid mt-5 pr-3 pl-3">
                                <p class="mt-4 desc">WEB <br> DEVELOPEMENT</p>
                            </div>

                            <div class="sub-divs-2">
                                <img src="./../../assets/header/body/web.svg" class="img-fluid mt-4">
                                <p class="mt-4 desc">WEB <br> DESIGN</p>
                            </div>
                        </div>

                        <div class="col-md-4 par4">
                            <div class="sub-divs-1">
                                <img src="./../../assets/header/body/coding.svg" class="img-fluid mt-4">
                                <p class="mt-4 desc">MOBILE APP <br> DEVELOPEMENT</p>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- right col -->
                <div class="col-md-5 intro-parent">
                    <p class="heading">WHAT WE DO</p>
                    <p class="intro-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
                        Quidem error fugiat soluta facere doloribus dolorum iusto cupiditate in ullam quod, ex odio inventore. 
                        Asperiores, placeat exercitationem perspiciatis aliquam molestiae ipsa!</p>
                </div>
            </div>

        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'WhatWeDo'
}
</script>

<style scoped>
 .WhatWeDo{
    height: 940px;
    background-image: url("./../../assets/header/body/path-68.svg");
    background-repeat: no-repeat;
 }
 /* left */
 .par{    
    margin: 300px 0 0 -50px;
 }
 .par4{    
    margin: 300px 0 0 -50px;
 }
 .sub-divs-1{
    border-radius: 3px;
    box-shadow: 0px 5px 0.9 11px black !important;
    background-color: white !important;
    height: 302px;
    width: 216px;
    text-align: center;
 }
 .desc{
     font-size: 16px;
     font-family: "Montserrat";
     font-weight: bold;
 }
 .middle-parent{
     margin: 150px 50px 0 20px;
     display: flex;
     flex-wrap: wrap;
 }
 .sub-divs-2{
    border-radius: 3px;
    box-shadow: 0px 5px 0.9 11px black;
    background-color: white !important;
    height: 281px;
    width: 216px !important;
    text-align: center;
 }
 /* right */
 .intro-parent{
    padding: 0 0 0 50px;
     margin: 340px 0 0 0;
     flex-wrap: wrap;
     text-align: center;
     align-items: center;
 }
 .heading{
     text-align: left;
     font-size: 30px;
     font-weight: bold;
     font-family: "Montserrat";
     color: rgb(22, 22, 22);
 }
 .intro-text{   
     text-align: left;
     font-family: "Montserrat";
     font-size: 16px;
     color: rgb(132, 132, 132);
     line-height: 28px;
 }

 /* media */
  @media only screen and (max-width: 1201px) {
    .sub-divs-1 {
        height: 250px;
        width: 150px;
    }
 }  

 @media only screen and (max-width: 768px) {
    .par {
        margin: 70px 60px 0 0;
        display: flex;
        justify-content: center;
    }
    .sub-divs-2 {
        height: 230px;    
        margin: 0 20px 0 0;
    }   
    .middle-parent{
        margin: 10px 0 10px 110px;
    }
    .left{
        justify-content: center;
        margin-right: 5px;
    }
    .par4{
        display: flex;
        justify-content: center;
        margin: 5px 90px 0 0;
    }
    .WhatWeDo {
        height: 1300px;
    }
    .intro-parent{
        margin: 30px 0 0 0;
        padding: 0 0 0 0;
        margin: 30px 0 0 0;
    }
    .heading{
         text-align: center;
    }
    .left{
        margin-bottom: 10px !important;
    }
 }   
  @media only screen and (max-width: 547px) {
    .par {
        margin: 40px 0 0 0;
    }
    .sub-divs-2 {
        margin: 0;
    }   
    .middle-parent{
        margin: 40px 0 0 110px;
    }
    .par4{
        display: flex;
        justify-content: center;
        margin: 50px 0 0 0;
    }
    .WhatWeDo {
        height: 1400px;
    }
    .intro-parent{
    padding: 0 0 0 0;
     margin: 30px 0 0 0;
    }
    .heading{
     text-align: center;
    }
 }   
</style>
    
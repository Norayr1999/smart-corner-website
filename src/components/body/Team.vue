<template>
    <div class="team" id="team">
        <div class="container-fluid">
            <div class="container-xl">
          
                <div class="row">
                    <div class="col-md-12">
                        <p class="heading">Met Our Team</p>
                    </div>
                </div>

                <div class="row">
                    <div class="col-md-12">
                        <p class="heading2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. <br>
                            Iste ullam recusandae atque iusto libero architecto </p>
                    </div>
                </div>

                <div class="row info">
                    <div class="col-xl-3">
                        <p class="content">Smart Corner is a fast growing Web Development company based in Yerevan, Armenia. <br>
                            Smart Corner was founded in 2015 in Armenia and has its branch in the USA, as well.<br> 
                            The range of the services we offer include Website development, Web application development, 
                            Web design, Redesign, Maintenance Web Hosting, Graphic Design, Logo Design, SEO. <br>
                            We work with both local business owners and international companies. 
                            </p>
                    </div>

                    <div class="col-xl-9">
                        <div class="teamPic">
                            <!-- main picture -->
                            <img src="./../../assets/header/body/all-team.jpg" class="img-fluid">
                            <!-- Components -->
                            <div class="icon1-hover curs">
                                <img src="./../../assets/header/body/Gexec.png" class="icon1 icons">
                            </div>

                            <div class="icon2-hover curs">
                                <img src="./../../assets/header/body/Aram.png" class="icon2 icons">
                            </div>

                            <div class="icon3-hover curs">
                                <img src="./../../assets/header/body/Artush.png" class="icon3 icons">
                            </div>

                            <div class="icon4-hover curs">
                                <img src="./../../assets/header/body/Sasun.png" class="icon4 icons">
                            </div>

                            <div class="icon5-hover curs">
                                <img src="./../../assets/header/body/Lil.png" class="icon5 icons">
                            </div>

                            <div class="icon6-hover curs">
                                <img src="./../../assets/header/body/Harut.png" class="icon6 icons">
                            </div>

                        </div>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Team'
}
</script>

<style scoped>
 .team{
    height: 1172px;
    padding: 50px 0 0 0;
    background-image: url("./../../assets/header/body/path-69.svg");
    background-repeat: no-repeat;
    background-size: contain;
    position: inherit;
 }
 .heading{
     text-align: center;
     font-size: 30px;
     color: white;
 }
 .heading2{
     text-align: center;
     font-size: 16px;
     color: white;
 }
 .info{
     margin-top: 50px;
 }
 .content{
    border-radius: 3px;
    background-color: rgba(237, 110, 0, 1);
    height: 100%;
    font-family: "Montserrat";
    font-size: 16px;
    color: white;
    padding: 10px; 
 }
 .teamPic{
     position: relative;
 }
 img, .curs{
    cursor: url(./../../assets/header/body/Ellipse33.png), auto;
 }
 .icons{
     position: absolute;
 }

/* =========================== icons =============================== */
 .icon1{
    z-index: 999;
    height: 100px;
    width: 100px;
    top: 40px;  
    left: -4px;
    display: none;
 }
 .icon2{
    z-index: 999;
    height: 150px;
    width: 145px;
    top: -55px;
    left: -12px;
    display: none; 
 }
 .icon3{
    z-index: 999;
    height: 45px;
    width: 58px;
    top: 22px;
    left: 9px;    
    display: none;
 }
 .icon4{
    z-index: 999;
    height: 75px;
    width: 30px;
    top: 42px;
    left: 25px; 
    display: none;   
 }
 .icon5{
    z-index: 999;
    height: 45px;
    width: 54px;
    top: -22px;
    left: 15px; 
    display: none;
 }
 .icon6{
    z-index: 999;
    height: 20px;
    width: 40px;
    top: 35px;
    left: 22px; 
    display: none;
 }

 /*=============================== hover container =================================== */
 .icon1-hover{
     position: absolute;
     height: 120px;
     width: 80px;
     top: 150px;
     right: 3%;
 }
 .icon1-hover:hover > .icon1 { 
     display: block;
 }

  .icon2-hover{
     position: absolute;
     height: 120px;
     width: 70px;
     top: 150px;
     right: 14%;
 }
 .icon2-hover:hover > .icon2 { 
     display: block;
 }

 .icon3-hover{
     position: absolute;
     height: 170px;
     width: 75px;
     top: 140px;
     right: 23%;
 }
 .icon3-hover:hover > .icon3 { 
     display: block;
 }

 .icon4-hover{
     position: absolute;
     height: 150px;
     width: 75px;
     top: 140px;
     right: 32%;
 }
 .icon4-hover:hover > .icon4 { 
     display: block;
 }

 .icon5-hover{
     position: absolute;
     height: 150px;
     width: 75px;
     top: 140px;
     right: 41%;
 }
 .icon5-hover:hover > .icon5 { 
     display: block;
 }
 .icon6-hover{
     position: absolute;
     height: 150px;
     width: 75px;
     top: 140px;
     right: 49.5%;
 }
 .icon6-hover:hover > .icon6 { 
     display: block;
 }
 @media only screen and (max-width: 1200px) {
    .curs{
        
    }
    .team{
        height: 900px;
    }
    img{
        height: 300px;
        width: 700px;
    }
    .col-xl-9{
        text-align: center;
    }
    .icon1-hover{
        height: 80px;
        width: 50px;
        top: 150px;
        right: 3%;
    }
 }   
</style>
    
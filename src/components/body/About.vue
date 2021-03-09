<template>
  <div class="About mb-5 pb-5" id="about">
      <div class="container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-12">

                    <div class="row a">
                        <!-- about -->
                        <div class="col-md-5">
                            <div class="row">
                                <div class="col-md-12">
                                    <p class="head">About</p>
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-12">
                                    <p class="content">Smart Corner is a fast growing Web Development company based in Yerevan, Armenia. <br>
                                        Smart Corner was founded in 2015 in Armenia and has its branch in the USA, as well. <br>
                                        The range of the services we offer include Website development, Web application development, 
                                        Web design, Redesign, Maintenance Web Hosting, Graphic Design, Logo Design, SEO. 
                                        We work with both local business owners and international companies. <br><br>
                                        The most important things for us are high quality work, professional approach and desire 
                                        to excel at clients' expectations which always bring clients' satisfaction.</p>
                                </div>
                            </div>
                        </div>


                    <!-- picture -->
                        <div class="col-md-7">
                            <div class="img-parent">
                                <img src="./../../assets/header/body/Group92.svg" class="img-fluid">
                            </div>
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
  name: 'About'
}
</script>

<style scoped>
    .About{
        margin: 0;
        display: flex;
        align-items: center;
        height: 940px;
        background-image: url("./../../assets/header/body/path-68.svg");
        background-repeat: no-repeat;
        position: relative;
    }
    .head{
        text-align: left;
        font-family: "Montserrat";
        font-weight: bold;
        font-size: 30px;
    }
    .content{
        text-align: left;
        font-family: "Montserrat";
        font-size: 16px;
        color: rgba(132, 132, 132, 1);
    }
    .img-parent{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 466px;
    }
    .general{
        display: flex;
        justify-content: space-between;
    }
    .a{
        display: flex;
    }
</style>
    
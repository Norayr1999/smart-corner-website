<template>
  <div class="head" id="header">
      <div class="container-fluid">
        <div class="container">

    <!-- navbar -->

    <b-navbar toggleable="lg" type="light">
        <b-navbar-brand href="#">
            <img src="@/assets/header/logo.png" height="56px" width="153px">
        </b-navbar-brand>
        
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>     
                <b-navbar-nav class="ml-auto">
                    <b-nav-form>
                        <b-navbar-nav>
                            <b-nav-item href="#services">
                                <div class="a mr-3">Services</div>
                            </b-nav-item>

                            <b-nav-item href="#portfolio">
                                 <div class="a mr-3">Portfolio</div>
                            </b-nav-item>
                            
                            <b-nav-item href="#about">
                                <div class="a mr-3">About</div>
                            </b-nav-item>
                            
                            <b-nav-item href="#team">
                                <div class="a mr-3">Team</div>
                            </b-nav-item>
                            
                            <b-nav-item href="#contact">
                                <div class="a mr-3">Contacts</div>
                            </b-nav-item>
                        </b-navbar-nav>
                    </b-nav-form>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    
    <!-- header body -->

            <div class="row">
                <div class="col-md-12">

                    <div class="row">
                        <div class="col-md-7">  
                            <h4>Lorem Ipsum simply dummy text of the <br> printing and typesitting industyr.</h4>

                            <p class="intro"> 
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
                                Maxime saepe nobis placeat quos ea! Fugit unde est, voluptate sit quibusdam
                                impedit maiores officiis fugiat saepe, eligendi quia quasi voluptatibus facilis!
                            </p>
                        </div>
                        
                        <div class="col-md-4">  
                            
                        </div>
                        
                        <div class="col-md-1">  
                            <div class="links">
                                <a href="#" class="ml-4">Facebook</a>
                                <a href="#" class="ml-4">Tweeter</a>
                                <a href="#" class="ml-4">Pintrest</a>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

<!-- scroll down  -->
            <div class="row">
                <div class="col-md-12 scroll">

                    <div class="row">
                        <div class="col-md-1">  
                            <p class="links1">Scroll-Down</p>
                        </div>

                        <div class="col-md-11"></div>
                    </div>

                </div>
            </div>

        </div> 
      </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
.head{
    background-image: url("./../../assets/header/body/symbol-2.png");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    height: 900px;
}
/* navbar */
 nav{
    font-family: "SemiBold";
    width: 100%;
 }
 ul{
    width: 100%;
    display: flex;
    justify-content: flex-end;
    align-items: flex-start;
 }
 .a{
    color: black !important;
    font-size: 16px !important;
 }
 .a:hover{
    color: rgba(237, 110, 0, 1) !important; 
 }
 /* header body */
 h4{
    margin-top: 150px;
    line-height: 1.6;
    font-weight: bold;
    color: rgba(237, 110, 0, 1);
 }
 .intro{
    margin-top: 50px;
    font-size: 14px;
    line-height: 1.8;
 }
 .links{
    margin-top: 150px;
    transform: rotate(90deg);
 }
 .links > a{
    color: rgb(177, 177, 177);
    font-size: 12px;
 }
 .links1{
    width: 100%;
    color: rgb(177, 177, 177);
    font-size: 12px;            
    margin: 100px 0 0 -30px; 
    transform: rotate(90deg);
 }

 /* media query */
 @media only screen and (max-width: 770px) {
    .links {
        margin-top: 100px;
        transform: rotate(0deg);
    }
    .links > a{
        color: rgb(237, 110, 0);
    }
    .links1{ 
        color: rgba(237, 110, 0, 1);
        margin: 80px 0 0 25px; 
        transform: rotate(0deg);
    }
}
 
 @media only screen and (max-width: 525px) {
    .links > a{
        color: green;
    }
    .links1{ 
        color: green;
    }
}
</style>
    
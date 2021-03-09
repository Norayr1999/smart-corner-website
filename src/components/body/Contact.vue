<template>
  <div class="Contact pb-5" id="contact">
      <div class="container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-12">

                    <div class="row">
                        <div class="col-md-12">
                            <p class="head">Contact</p>
                        </div>
                    </div>
                    <!-- 1/4 -->
                    <div class="row mt-5">
                        <div class="col-md-3">
                            <div class="row">
                                <div class="col-md-12">
                                    <p class="headings">Adress</p>
                                </div>
                            </div>

                            <div class="row mb-5">
                                <div class="col-md-12 pic">
                                   <img src="./../../assets/header/body/address2.svg" img-fluid> 
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-12">
                                    <p class="info">Garegin Njdeh 46</p>
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-12">
                                    <p class="info">Armenia Yerevan, 37416.</p>
                                </div>
                            </div>
                        </div>
                        <!-- 2/4 -->
                        <div class="col-md-3">
                            <div class="row">
                                <div class="col-md-12">
                                    <p class="headings">Phone</p>
                                </div>
                            </div>

                            <div class="row mb-5">
                                <div class="col-md-12 pic">
                                   <img src="./../../assets/header/body/phon2.svg" img-fluid> 
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-12">
                                    <p class="info">+374 55 222 111</p>
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-12">
                                    <p class="info">+374 55 222 111</p>
                                </div>
                            </div>
                        </div>
                        <!-- 3/4 -->
                        <div class="col-md-3">
                            <div class="row">
                                <div class="col-md-12">
                                    <p class="headings">Email</p>
                                </div>
                            </div>

                            <div class="row mb-5">
                                <div class="col-md-12 pic">
                                   <img src="./../../assets/header/body/address2.svg" img-fluid> 
                                </div>
                            </div>

                            <div class="row col3">
                                <div class="col-md-12">
                                    <p class="info">info@smart-corner.org</p>
                                </div>
                            </div>
                        </div>
                        <!-- 4/4 -->
                        <div class="col-md-3">
                            <div class="row">
                                <div class="col-md-12">
                                    <p class="headings">Hours</p>
                                </div>
                            </div>

                            <div class="row mb-5">
                                <div class="col-md-12 pic">
                                   <img src="./../../assets/header/body/clock2.svg" img-fluid> 
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-12">
                                    <p class="info">Monday - Friday</p>
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-12">
                                    <p class="info">9:00 - 18:00</p>
                                </div>
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
  name: 'Contact'
}
</script>

<style scoped>
    .head{
        text-align: left;
        font-family: Montserrat;
        font-weight: bold;
        font-size: 30px;
        text-align: center;
    }
    .headings{
        text-align: center;
        font-family: Montserrat;
        font-weight: bold;
        font-size: 16px;
    }
    .pic{
        text-align: center;
    }
    .info{
        text-align: center;
        font-family: Montserrat;
        font-weight: bold;
        font-size: 16px;
        color: rgba(237, 110, 0, 1);
    }
    .col3{
        margin-top: 90px;
    }
    img{
        width: 60%;
    }
/* media */
@media only screen and (max-width: 768px) {
    .head{
        margin: 150px 0 0 0;
    }
    .headings{
        margin: 50px 0 10px 0;
    }
}
</style>
    
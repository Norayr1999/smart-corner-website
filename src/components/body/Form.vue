<template>
  <div class="Form">
      <div class="container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-12">

                    <div class="row">
                        <div class="col-md-2"></div>
                        <div class="col-md-8">
                            <form class="form">
                                <div class="row">
                                    <div class="col-md-12 inps-parent">
                                        <input type="email" class="form-control inps" aria-describedby="emailHelp" placeholder="Your Name">
                                        <input type="email" class="form-control inps" aria-describedby="emailHelp" placeholder="Phone Number">
                                    </div>
                                </div>

                                  <div class="row mt-5">
                                    <div class="col-md-12">
                                        <input type="textarea" class="form-control area" aria-describedby="emailHelp" placeholder="Your message">
                                    </div>
                                </div>  

                                <div class="row mt-5">
                                    <div class="col-md-12 btn-parent">
                                        <input type="button" class="form-control btn" aria-describedby="emailHelp" value="Your message">
                                    </div>
                                </div>
                            </form>
                        </div>
                        <div class="col-md-2"></div>
                    </div>
                    
                    <div class="goUp">
                        <a href="#header">
                            <i class="fas fa-chevron-up up"></i>
                        </a>
                    </div>
                
                </div>
            </div>
        </div> 
      </div>
  </div>
</template>

<script>
export default {
  name: 'Form'
}
</script>

<style scoped>
.up{
    color: rgba(237, 110, 0, 1);
    font-size: 20px;
}
.goUp{
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    width: 60px;
    position: absolute;
    bottom: -110px;
    left: 47%;
    border-radius: 100%;
    background-color: rgba(255, 255, 255, 0.1);
    box-shadow: 0px 3px 10px rgba(0, 0, 0, 0.09);
}
.Form{
    height: 520px;
    background-repeat: no-repeat;
    position: relative;
    background-image: url("./../../assets/header/body/path-72.svg");
}
.form{
    border-radius:3px ;
    padding: 25px 50px 60px 50px;
    box-shadow: 0px 10px 19px rgba(0, 0, 0, 0.1);
}
  .btn{
      background-color: rgba(237, 110, 0, 1);
      color: white;
      width: 200px;
      height: 50px;
  }
  .btn-parent{
      text-align: center;
  }
  .inps-parent{
      display: flex;
      justify-content: space-between;
  }
  .inps{
      height: 50px;
      width: 48%;
  }
  .area{
      min-height: 100px;
  }
</style>
    
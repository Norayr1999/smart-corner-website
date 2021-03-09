<template>
  <div class="statistic mt-5 mb-2">
      <div class="container-fluid">
        <div class="container">

            <div class="row">
                <div class="col-md-12">

                    <div class="row">
                 
                        <div class="col-md-3">
                <!-- col 1 -->
                          <div class="row">
                            <div class="col-md-12 text">
                              <p>Complieted Projects</p>
                            </div>
                          </div>

                          <div class="row">
                            <div class="col-md-12 statistics-back">
                              <p class="mt-2">195</p>
                            </div>
                          </div>
                        </div>
                  <!-- col 2 -->
                        <div class="col-md-3">
                          <div class="row">
                            <div class="col-md-12 text">
                              <p>Satisfied Clients</p>
                            </div>
                          </div>

                          <div class="row">
                            <div class="col-md-12 statistics-back">
                              <p class="mt-2">85</p>
                            </div>
                          </div>
                        </div>
                  <!-- col 3 -->
                        <div class="col-md-3">

                          <div class="row">
                            <div class="col-md-12 text">
                              <p>Line of Code</p>
                            </div>
                          </div>

                          <div class="row">
                            <div class="col-md-12 statistics-back">
                              <p class="mt-2">989</p>
                            </div>
                          </div>
                        </div>
                  <!-- col 4 -->
                        <div class="col-md-3">
                          <div class="row">
                            <div class="col-md-12 text">
                              <p>Cup of Coffee</p>
                            </div>
                          </div>

                          <div class="row">
                            <div class="col-md-12 statistics-back">
                              <p class="mt-2">32400</p>
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
  name: 'Statistics'
}
</script>

<style scoped>
 .statistics-back{
   text-align: center;
   background-image: url("./../../assets/header/body/path-15.png");
   background-position: center;
    background-repeat: no-repeat;
    position: relative;
    font-size: 24px;
    font-weight: bold;
    color: rgba(237, 110, 0, 1);
 }
 .text{
   text-align: center;
 }
 p{
   margin-top: 50px;
 }
</style>
    
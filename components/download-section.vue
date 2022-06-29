<template>
    <section class="download-section">
        <div class="container">
             <div class="row">
                <div class="col-lg-6 col-sm-12 pt-5 pb-2">
                    <div class="row">
                        <div class="col-12">
                         <h1 class="dispaly-3"><b>Download app for<br> exciting deal</b></h1>
                        </div>
                        <div class="col-12 pt-2 pb-2">
                         <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.<br>It has been the industry's standard dummy text ever since. </p>
                        </div>
                        <div class="col-12 text-center">
                          <div class="row">
                            <div class="col-lg-3 col-sm-3">
                             <img src="@/assets/images/download/google.png" width="130px">
                            </div>
                            <div class="col-lg-3 col-sm-3 pt-2">
                            <img src="@/assets/images/download/app.png" width="110px">
                            </div>
                          </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6 col-sm-12 pl-3 text-center">
                     <img class="flip img-below" src="@/assets/images/download/veg.png" width="60%">
                      <img class="border-radius-20 img-over" src="@/assets/images/download/mobile.png" width="40%">
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:'DownloadSection'
}
</script>
<style scoped>
.download-section{
 background-color: #fee7d3;
 padding-top: 120px;
 padding-bottom: 120px;
 margin-bottom: 0%;
}
.border-radius-20{
 border-radius: 20px;
}
.flip{
  -webkit-transform: scaleX(-1);
  transform: scaleX(-1);
}
.img-below
{
  position: relative;
  top: 0;
  left: 0;
}
.img-over
{
  position: absolute;
  bottom: -79px;
  left: 210px;
}
</style>
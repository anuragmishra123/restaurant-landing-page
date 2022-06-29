<template>
    <section class="service-section">
        <div class="container">
          <div class="row">
          <div class="col-lg-6 col-sm-12">
             <h1>Our Services</h1>
          </div>
          <div class="col-lg-6 col-sm-12">
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.<br>It has been the industry's standard dummy text ever since. </p>
          </div>
          </div>
          <div class="row pt-5">
          <div class="col-lg-6 col-sm-12 mb-2">
            <div class="container">
            <div class="row">
               <div class="col-6 bg-card text-center ">
                 <img class="pt-3" src="@/assets/images/service/meeting.png" width="80px">
               </div>
               <div class="col-6">
                 <h5>advanced table <br>booking</h5><br>
                 <p>Lorem Ipsum is simply dummy text of the printing</p>
               </div>
            </div>
            <div class="row pt-3">
               <div class="col-6">
                 <h5>free for food<br>24/7</h5><br>
                 <p>Lorem Ipsum is simply dummy text of the printing</p>
               </div>
               <div class="col-6 bg-card text-center ">
                  <img class="pt-3" src="@/assets/images/service/dish.png" width="80px">
               </div>
            </div>
            </div>
          </div>
          <div class="col-lg-6 col-sm-12">
            <div class="row text-center bg-card pt-5 pb-5">
                <div class="col-12">
                   <img src="@/assets/images/service/scooter.png" width="100px">
                </div>
                <div class="col-12">
                   <h5>free home delivery<br> at your Doorsteps</h5>
                </div>
                <div class="col-12">
                    <p>Lorem Ipsum is simply dummy text <br>of the printing and typesetting industry.</p>
                </div>
            </div>
          </div>
          </div>
        </div>
    </section>
</template>
<script>
export default{
    name:'ServiceComponent'
}
</script>
<style scoped>
.bg-card{
    background-color: #ffedde;
}
.service-section{
 background-color: #FFF5EC;
 padding-top: 70px;
 padding-bottom: 70px;
 margin-bottom: 0%;
}
</style>
<template>
<section class="booking-section">
<div style="float: left">
<img src="@/assets/images/booking/leaf.png"  width="500px"/>
</div>
<div style="float: right">
<img src="@/assets/images/download/veg.png" width="450px"/>
</div>
 <div class="container">
    <div class="card">
        <div class="card-body">
            <div class="row">
              <div class=" col-lg-12 col-sm-12 d-flex justify-content-center">
               <div class="red-box"></div>
              </div>
              <div class="col-lg-12 col-sm-12 text-center pb-4">
                <h3>advanced booking</h3>
              </div>
              <div class="col-lg-12 col-sm-12 text-center d-flex justify-content-center pb-4">
                <div class="buttonIn ">
                    <input id="enter" type="text" class="form-control">
                    <button class="">GO</button>
                </div>
              </div>
              <div class="col-lg-12 col-sm-12 text-center pb-4">
                <ul>
                <li>cities</li>
                <li>customer</li>
                <li>benefits</li>
                </ul>
              </div>
            </div>
        </div>
    </div>
 </div>
</section>
</template>
<script>
export default{
    name:"BookingSection"
}
</script>
<style scoped>
.booking-section{
 background-color: #ffedde;
 padding-top: 80px;
 padding-bottom: 80px;
 margin-bottom: 0%;
}
ul li {
    display: inline;
}
.buttonIn {
    width: 300px;
    position: relative;
}
button {
    position: absolute;
    top: 0;
    border-radius: 2px;
    right: 0px;
    z-index: 2;
    border: none;
    height: 40px;
    width:100px;
    cursor: pointer;
    color: white;
    background-color: #fe043c;
    transform: translateX(2px);
}
.red-box{
    padding: 3px;
    background-color: red;
    width: 85px;
}
</style>
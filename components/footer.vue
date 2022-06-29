<template>
<footer id="footer" class="footer">
    <div class="container">
      <div class="row p-0">
        <div class="col-12 p-5 text-center">
         <h1>Get notified<br> about new amazing products</h1>
        </div>
        <div class="col-12 p-3 text-center">
         <h5>Lorem Ipsum is simply dummy text of the printing and typesetting industry.<br>It has been the industry's standard dummy text ever since. </h5>
        </div>
        <div class="col-12 p-2 text-center d-flex justify-content-center">
          <div class="row">
            <div class="col-12 ">
                <div class="input-group p-5">
                    <input class="form-control py-3 rounded-pill mr-1 pr-5" type="E-mail" value="E-mail" >
                    <span class="input-group-append">
                        <button class="btn rounded-pill border-0 ml-n5 pt-0" type="button">
                            <img src="@/assets/images/footer/arrow.png">
                        </button>
                    </span>
                </div>
            </div>
          </div> 
        </div>
        <div class="col-12 text-center">
            <ul id="horizontal-list">
                <li>Product</li>
                <li>Company</li>
                <li>Learn More</li>
                <li>Get in touch</li>
            </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
    name:'Footer'
}
</script>
<style scoped>
.footer{
 background-color: #FFF5EC;
 padding-top: 70px;
 padding-bottom: 70px;
 margin-bottom: 0%;
}
/* .form-control{
    max-width: max-content;
} */
ul#horizontal-list li {
    display: inline;
}
</style>
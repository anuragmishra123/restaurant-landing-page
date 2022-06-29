<template>
    <section class="explore-section">
        <div class="container">
           <div class="row text-center pb-3">
            <div class="col-12">
               <h3>Explore Our Foods</h3>
            </div>
            </div>
            <div class="row text-center pb-3">
                <div class="col-12">
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.<br>It has been the industry's standard dummy text ever since. </p>
                </div>
            </div>
            <div class="row text-center">
                <div v-for="(val,index) in items" :key="index" class="col-lg-4 col-md-4 col-sm-12">
                    <div  class="card mt-3" style="width: 18rem;border-radius: 15px;">
                        <img class="card-img-top" :src="val" alt="Card image cap">
                        <div class="card-body">
                            <div class="d-flex justify-content-between ">
                                <h5 class="card-title">Ham Sandwich</h5>
                                <h5>$10.50</h5>
                            </div>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:'ExploreSection',
    data(){
        return{
            items:[
                require('@/assets/images/explore/dish1.png'),
                require('@/assets/images/explore/dish2.png'),
                require('@/assets/images/explore/dish3.png'),
                require('@/assets/images/explore/dish4.png'),
                require('@/assets/images/explore/dish5.png'),
                require('@/assets/images/explore/dish6.png')
            ]
        }
    }
}
</script>
<style scoped>
.explore-section{
 background-color: #FFF5EC;
 padding-top: 70px;
 padding-bottom: 70px;
 margin-bottom: 0%;
}
</style>
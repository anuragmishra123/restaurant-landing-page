<template>
<div>
  <bookingSection/>
  <serviceSection/>
  <exploreSection/>
  <downloadSection/>
  <Footer/>
</div>
</template>
<script>
import bookingSection from "@/components/booking-section.vue"
import serviceSection from "@/components/service-section.vue"
import exploreSection from "@/components/explore-section.vue"
import downloadSection from "@/components/download-section.vue"
import Footer from "@/components/footer.vue"
export default {
  name:'Home',
  components:{
    bookingSection,
    serviceSection,
    exploreSection,
    downloadSection,
    Footer
  }
}
</script>

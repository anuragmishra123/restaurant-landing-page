<template>
<div>
  <exploreSection/>
  <downloadSection/>
  <Footer/>
</div>
</template>
<script>
import exploreSection from "@/components/explore-section.vue"
import downloadSection from "@/components/download-section.vue"
import Footer from "@/components/footer.vue"
export default {
  name:'Home',
  components:{
    exploreSection,
    downloadSection,
    Footer
  }
}
</script>

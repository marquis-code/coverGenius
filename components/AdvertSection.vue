<template>
  <main>
    <VueSlickCarousel>
       <div>
            <b-container class="pt-5 d-block d-lg-flex justify-content-between align-items-center">
       <div class="">
          <h3 class="header text-wrap font-weight-bold" style="width : 18rem;">Conveniently manage your plans and staff</h3>
          <p class="text-muted"><small>If a staff leaves, no worries! Seamlessly re-assign their plan to new staff from your dashboard. You can also;</small></p>
          <div>
              <div class="shadow-sm d-flex align-items-center indicator1" >
                 <p class="hover:text-black text-muted pt-3 pl-2"><small>Track Claims</small></p>
              </div>

              <div class="shadow-sm d-flex align-items-center indicator2 my-2">
                 <p class="hover:text-black text-muted pt-3 pl-2"><small>Manage Staff</small></p>
              </div>

              <div class="shadow-sm d-flex align-items-center indicator3">
                 <small class="text-xs pl-2">Access your insurance plans</small>
              </div>
          </div>
       </div>
       <div class="d-flex justify-content-center align-items-center">
         <img src="@/static/img/claim.svg" alt="claims" />
       </div>
  </b-container>
       </div>
    </VueSlickCarousel>
  </main>
</template>
 
<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
  name: 'AdvertSection',
  components: { VueSlickCarousel },
}
</script>

<style scoped>
   .header {
    color: #094063;
   }

   /* img {
    height: 30px;
   } */

   .indicator1 {
    height: 40px;
    border-left: 5px solid rgb(154, 81, 206);
   }

    .indicator2 {
    height: 40px;
    border-left: 5px solid rgb(217, 73, 73);
   }

    .indicator3 {
    height: 40px;
    border-left: 5px solid lightskyblue;
   }

</style>
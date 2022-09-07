<template>
   <main>
      <div>
         <VueSlickCarousel :arrows="false" :dots="false" :autoplay="true" :lazyLoad="true">
            <div>
               <b-container class="pt-5">
                  <p class="text-success font-weight-light text-center py-5">Transforming the insurance experience</p>
                  <h1 class="header text-center pb-3">Do business without disruptions</h1>
                  <p class="text-center text-muted">Our unique solution allows smoother operations which is suitable for every kind of logistic business.</p>
                  <div class="d-block d-lg-flex justify-content-between align-items-center pt-5">
                     <div class="px-1 px-lg-0">
                        <img src="@/static/img/icon1.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">All-round protection</h5>
                        <p class="text-light text-muted"><small>Get total coverage for any damages to your vehicles, goods, or riders in transit - without strain on your business.</small></p>
                     </div>
                     <div class="px-lg-5 px-1  mx-lg-2 mx-0">
                        <img src="@/static/img/icon2.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">Easy claims settlements!</h5>
                        <p class="text-light text-muted"><small>You won’t spend time filing papers or long forms with our digital claim process.</small></p>
                     </div>
                     <div class="px-1 px-lg-0">
                        <img src="@/static/img/icon3.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">Budget-friendly</h5>
                        <p class="text-light text-muted"><small>With a yearly payment of ₦25,000 per rider (the goods in transit and vehicle), you can easily plan and save on budget.</small></p>
                     </div>
                  </div>
               </b-container>
            </div>

                 <div>
               <b-container class="pt-5">
                  <p class="text-success font-weight-light text-center py-5">Why choose us?</p>
                  <h1 class="header text-center pb-3">Get insurance the way you need it</h1>
                  <p class="text-center text-muted">We relieve you of the financial risks involved with vehicle
                     incidents on transit.</p>
                  <div class="d-block d-lg-flex justify-content-between align-items-center pt-5">
                     <div class="px-1 px-lg-0">
                        <img src="@/static/img/icon4.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">Complete Protection</h5>
                        <p class="text-light text-muted"><small>Our plan gives you the maximum amount of coverage for
                              any damages to your vehicles, without strain on your business.</small></p>
                     </div>
                     <div class="px-lg-5 px-1  mx-lg-2 mx-0">
                        <img src="@/static/img/icon5.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">Cost-effective</h5>
                        <p class="text-light text-muted"><small>Our auto coverage works for you, to reduce the financial
                              strain on your budget. This is not insurance from ‘one agent like that’</small></p>
                     </div>
                     <div class="px-1 px-lg-0">
                        <img src="@/static/img/icon6.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">Peace of mind</h5>
                        <p class="text-light text-muted"><small>This plan also covers third-party damages for legal
                              compliance, so you can drive peace of mind.</small></p>
                     </div>
                  </div>
               </b-container>
            </div>

                 <div>
               <b-container class="pt-5">
                  <p class="text-success font-weight-light text-center py-5">Smart insurance solution</p>
                  <h1 class="header text-center pb-3">One less worry off your budget</h1>
                  <p class="text-center text-muted">Secure your mobile phones, laptops and similar devices used for business.
</p>
                  <div class="d-block d-lg-flex justify-content-between align-items-center pt-5">
                     <div class="px-1 px-lg-0">
                        <img src="@/static/img/icon5.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">Save on budget</h5>
                        <p class="text-light text-muted"><small>Buying devices and repairs can break the bank. We give discounts for multiple devices while helping you save on repair cost.
</small></p>
                     </div>
                     <div class="px-lg-5 px-1  mx-lg-2 mx-0">
                        <img src="@/static/img/icon2.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">Convenience</h5>
                        <p class="text-light text-muted"><small>Our claims process is fast and seamless with dedicated repair partners at your beck and call. Fixing your device takes less than 24 - 72 hours. </small></p>
                     </div>
                     <div class="px-1 px-lg-0">
                        <img src="@/static/img/icon1.svg" alt="icon" class="pb-4" />
                        <h5 class="header pb-2">90 Days Warranty</h5>
                        <p class="text-light text-muted"><small>Every screen replaced comes with a 90 day warranty, so you have peace of mind. We are all about quality.</small></p>
                     </div>
                  </div>
               </b-container>
            </div>
         </VueSlickCarousel>
      </div>
   </main>
</template>
 
<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
   name: 'WhyChoseUs',
   components: { VueSlickCarousel },
}
</script>

<style scoped>
.header {
   color: #094063;
}
</style>
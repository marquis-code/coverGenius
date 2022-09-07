<template>
  <main cl>
    <VueSlickCarousel
     :arrows="true"
    :dots="false"
    :autoplay="true"
    :lazyLoad="true"
    >
      <div>
        <b-container class="pt-5 px-4 px-lg-0">
          <h3 class="header text-wrap font-weight-bold" style="width : 10rem; font-size: xx-large;">Seamless insurance  coverage for every<br />
            logistics service</h3>
          <p class="text-muted py-2 font-weight-light text-size-small text-wrap" style="width : 23rem;">Businesses can
            now protect their riders, vehicles<br /> and goods in transit with our custom-made<br /> Delivery Cover.</p>
        </b-container>
      </div>
      <div>
        <b-container class="pt-5 px-4 px-lg-0">
          <h3 class="header text-wrap font-weight-bold" style="width : 25rem;">Protect the vehicles <br /> that drive growth in <br />
            your
            business</h3>
          <p class="text-muted py-2 font-weight-light text-size-small text-wrap" style="width : 23rem;">Minimize
            business risks with our one-stop<br /> Auto Insurance for all your vehicle needs.</p>
        </b-container>
      </div>
      <div>
        <b-container class="pt-5 px-4 px-lg-0">
          <h3 class="header text-wrap font-weight-bold" style="width : 25rem;">Complete insurance <br /> for your business <br />
            gadgets</h3>
          <p class="text-muted py-2 font-weight-light text-size-small text-wrap" style="width : 23rem;">Let’s protect
            all the devices in your business<br /> and take care of the repair costs with<br /> Gadget Cover.</p>
        </b-container>
      </div>
    </VueSlickCarousel>
   <b-container>
      <button class="py-2 px-4 rounded-lg border button"><small class="text-white font-weight-light">Get Covered</small></button>
   </b-container>
  </main>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
  name: 'Introduction',
  components: { VueSlickCarousel },
}
</script>

<style scoped>
.button {
  background-color: #439687;
}

.header {
  color: #094063;
}
</style>

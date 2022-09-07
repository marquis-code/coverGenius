<template>
    <main>
        <VueSlickCarousel :arrows="false" :dots="false" :autoplay="true" :lazyLoad="true">
            <div>
                <b-aspect aspect="16:9" class="background1 d-flex justify-content-between align-items-center">
                    <b-container class="d-block d-lg-flex justify-content-between align-items-center mt-5 h-50">
                        <div class="">
                            <p class="text-success font-weight-light">Seamless insurance experience</p>
                            <h3 class="header text-wrap font-weight-bold" style="width : 25rem;">Ship goods with<br /> confidence</h3>
                            <p class="text-muted py-2 font-weight-light text-size-small text-wrap"
                                style="width : 25rem;">What do you do when your vehicle stops midway while  delivering a package? This could be due to an accident, or minor collisions. Delivery cover enables you to save face before customers and for happier riders.
                            </p>
                        </div>
                        <div class="background2 d-flex justify-content-center align-items-center p-2 ml-2">
                           <div class="imageContainer">
                               <div><img src="@/static/img/ridercover.svg" alt="" class="cover border-t-red" /></div>
                                <div><img src="@/static/img/rider.svg" alt="" class="rider border-t-red" /></div>
                           </div>
                        </div>
                    </b-container>
                </b-aspect>
            </div>

            <div>
                <b-aspect aspect="16:9" class="background1 d-flex justify-content-between align-items-center">
                    <b-container class="d-block d-lg-flex justify-content-between align-items-center mt-5 h-50">
                        <div class="">
                            <p class="text-success font-weight-light">Why Auto Insurance?</p>
                            <h3 class="header text-wrap font-weight-bold" style="width : 25rem;">Your vehicle's care<br /> is
                                our
                                business</h3>
                            <p class="text-muted py-2 font-weight-light text-size-small text-wrap"
                                style="width : 25rem;">Setting up
                                any business is not an easy feat, coupled with the
                                risks that come with managing vehicles. Our comprehensive insurance
                                plan gives you complete coverage for your vehicles you covered.
                            </p>
                        </div>
                        <div class="background2 d-flex justify-content-center align-items-center p-2 ml-2">
                            <img src="@/static/img/animatedCar.svg" alt="" class="border-t-red" />
                        </div>
                    </b-container>
                </b-aspect>
            </div>

            <div>
                <b-aspect aspect="16:9" class="background1 d-flex justify-content-between align-items-center">
                    <b-container class="d-block d-lg-flex justify-content-between align-items-center mt-5 h-50">
                        <div class="">
                            <p class="text-success font-weight-light">Do business smartly</p>
                            <h3 class="header text-wrap font-weight-bold" style="width : 25rem;">Leave the little things<br /> for us to worry about
</h3>
                            <p class="text-muted py-2 font-weight-light text-size-small text-wrap"
                                style="width : 25rem;">It can be frustrating when your devices gets damaged while working. It gets more frustrating when you bear the high cost of fixing it outside your budget. We bearthe cost of fixing screen damages and liguide spills to  your devices with an affordable Gadget Cover. 
                            </p>
                        </div>
                        <div class="background2 d-flex justify-content-center align-items-center p-2 ml-2">
                            <img src="@/static/img/gadgets.svg" alt="" class="border-t-red" />
                        </div>
                    </b-container>
                </b-aspect>
            </div>
        </VueSlickCarousel>
    </main>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
    name: 'Insurance',
    components: { VueSlickCarousel },
}
</script>

<style scoped>
.background1 {
    background-image: url('@/static/img/bgRectangle.svg');
    background-repeat: no-repeat;
    background-size: cover;
}

.background2 {
    background-image: url('@/static/img/bgSquare.svg');
    background-repeat: no-repeat;
    background-size: cover;
}
.header {
    color: #094063;
}

.imageContainer {
    position: relative;
}

.cover{
    position: absolute;
    top: -30px;
    right: 60px;
    
}

.rider{
    margin-top: 60px;
}
</style>
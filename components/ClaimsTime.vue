<template>
    <main>
        <VueSlickCarousel :arrows="false" :dots="false" :autoplay="true" :lazyLoad="true">
            <div>
                <b-aspect aspect="16:9" class="background1 d-flex justify-content-between align-items-center">
                    <b-container class="sectionContainer d-block d-lg-flex justify-content-between align-items-center mt-5 h-50">
                        <div class="">
                            <p class="text-success font-weight-light">100% Claims Assessments</p>
                            <h3 class="header text-wrap font-weight-bold py-5" style="width : 22rem;">Make Claims in
                                <span class="textColor text-white rounded-circle">15</span>minutes, not 2 months
                            </h3>
                            <div class="d-flex align-items-center pb-2">
                                <div class="pr-3"><img src="@/static/img/coloredIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="pb-0">Report Claim</h6>
                                    <small class="text-muted">It all starts with a click. Log in to your dashboard
                                        from
                                        your device.</small>
                                </div>
                            </div>
                            <div class="d-flex align-items-center pb-2">
                                <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="text-muted">Take Picture</h6>
                                </div>
                            </div>
                            <div class="d-flex align-items-end pb-2">
                                <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="text-muted">Estimate damage</h6>
                                </div>
                            </div>
                            <div class="d-flex align-items-end">
                                <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="text-muted">Get Paid</h6>
                                </div>
                            </div>
                        </div>
                        <div class="background2 d-flex justify-content-center align-items-center align-lg-items-end mt-5 p-4">
                            <img src="@/static/img/phone.svg" alt="" class="phone border-t-red pb-1" />
                        </div>
                    </b-container>
                </b-aspect>
            </div>

            <div>
                <b-aspect aspect="16:9" class="background1 d-flex justify-content-between align-items-center">
                    <b-container class="sectionContainer d-block d-lg-flex justify-content-between align-items-center mt-5 h-50">
                        <div class="">
                            <p class="text-success font-weight-light">Seamless claims experience</p>
                            <h3 class="header text-wrap font-weight-bold py-5" style="width : 22rem;">Get quick repairs and<br /> replacements
                            </h3>
                            <div class="d-flex align-items-center pb-2">
                                <div class="pr-3"><img src="@/static/img/coloredIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="pb-0">Report Claim</h6>
                                    <small class="text-muted">Our repair partners come to you, wherever you to fix yoru devices, so ,<br />you don’t have to do anything. This is only available within Lagos State.
</small>
                                </div>
                            </div>
                            <div class="d-flex align-items-center pb-2">
                                <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="text-muted">Take Picture</h6>
                                </div>
                            </div>
                            <div class="d-flex align-items-end pb-2">
                                <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="text-muted">Schedule visit</h6>
                                </div>
                            </div>
                            <div class="d-flex align-items-end">
                                <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image" />
                                </div>
                                <div>
                                    <h6 class="text-muted">Get devices fixed</h6>
                                </div>
                            </div>
                        </div>
                        <!-- <div class="background2 d-flex justify-content-center align-items-end mt-5 p-4">
                            <img src="@/static/img/phone.svg" alt="" class="border-t-red pb-1" />
                        </div> -->
                        <div class="background2 d-flex justify-content-center align-items-center align-lg-items-end mt-5 p-4">
                            <img src="@/static/img/phone.svg" alt="" class="phone border-t-red pb-1" />
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
    name: 'ClaimsTime',
    components: { VueSlickCarousel },
}
</script>

<style scoped>
.background1 {
    background-image: url('@/static/img/rectangle2.svg');
    background-repeat: no-repeat;
    background-size: cover;
}

.background2 {
    background-image: url('@/static/img/circle.svg');
    background-repeat: no-repeat;
    background-size: cover;
    /* width: 560px;
    height: 560px; */
    width: 400px;
    height: 400px;
}

.phone {
    width: 350px;
    height: 350px;
}

.header {
    color: #094063;
}

.image {
    height: 50px;
}

.textColor {
    background-color: rgb(168, 74, 235);
}

.sectionContainer {
    padding-top: 90px;
}
</style>
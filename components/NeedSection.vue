<template>
    <main class="background mt-5">
        <VueSlickCarousel >
            <div>
                <b-container class="py-5">
                    <div class="d-block d-lg-flex justify-content-between align-items-center pt-5">
                        <div class="pr-5 pb-4 pb-lg-0">
                            <p class="text-success font-weight-light pb-4">3 covers rolled up in one</p>
                            <h4 class="header text-wrap font-weight-bold" style="width : 20rem;">Get a 360° Cover for
                                your logistics business against accidental damages.</h4>
                        </div>
                        <div class="">
                            <div class="d-flex align-items-start">
                                <div class="pr-3"><img src="@/static/img/ellipse1.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h6 class="header display-7">Comprehensive auto insurance for your bikes/vehicles</h6>
                            </div>
                            </div>
                            <div class="d-flex align-items-start py-3">
                                <div class="pr-3"><img src="@/static/img/ellipse2.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h6 class="header display-7">Personal accident cover (PAC) for staff.</h6>
                            </div>
                            </div>
                            <div class="d-flex align-items-start">
                                <div class="pr-3"><img src="@/static/img/ellipse3.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h6 class="header display-7">Cover for damages to your goods in transit (GIT).</h6>
                            </div>
                            </div>
                        </div>
                    </div>
                </b-container>
            </div>

            <!-- <div>
                <b-container class="py-5">
                    <div class="d-flex justify-content-between align-items-center pt-5">
                        <div class="pr-5">
                            <p class="text-success font-weight-light pb-4">What is covered in Auto Insurance?</p>
                            <h3 class="header text-wrap font-weight-bold" style="width : 20rem;">One solution<br /> for your
                                vehicle<br />
                                needs</h3>
                            <p class="text-muted">All the protection you need is right here, so you can drive growth in
                                your
                                business.</p>
                        </div>
                        <div class="pl-5">
                            <div class="d-flex align-items-start">
                                <div class="pr-3"><img src="@/static/img/ellipse1.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h7 class="header">Vehicle damages</h7>
                                    <p class="text-muted"><small> cover financial losses due to accidental damages to
                                            your
                                            company’s assets during transit.</small></p>
                                </div>
                            </div>
                            <div class="d-flex align-items-start">
                                <div class="pr-3"><img src="@/static/img/ellipse2.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h7 class="header">Third-party wahala</h7>
                                    <p class="text-muted"><small>Our policies save face and keep you worry-free when
                                            there are
                                            accidental damages to other vehicles or their riders.</small></p>
                                </div>
                            </div>
                            <div class="d-flex align-items-start">
                                <div class="pr-3"><img src="@/static/img/ellipse3.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h7 class="header">Bodily Injuries</h7>
                                    <p class="text-muted"><small> also compensate for damages to riders and drivers
                                            involved to
                                            keep business running smoothly.</small></p>
                                </div>
                            </div>
                        </div>
                    </div>
                </b-container>
            </div> -->

            <!-- <div>
                <b-container class="py-5">
                    <div class="d-flex justify-content-between align-items-center pt-5">
                        <div class="pr-5">
                            <p class="text-success font-weight-light pb-4">Smart insurance covers</p>
                            <h3 class="header text-wrap font-weight-bold" style="width : 20rem;">A unique insurance<br />
                                solution for<br /> devices</h3>
                            <p class="text-muted">Get the protection for your devices you need to<br /> keep your business
                                running.
                            </p>
                        </div>
                        <div class="pl-5">
                            <div class="d-flex align-items-start">
                                <div class="pr-3"><img src="@/static/img/ellipse1.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h7 class="header">Screen damages</h7>
                                    <p class="text-muted"><small>Get coverage against accidental screen cracks, drips
                                            and breakages for every device.
                                        </small></p>
                                </div>
                            </div>
                            <div class="d-flex align-items-start">
                                <div class="pr-3"><img src="@/static/img/ellipse2.svg" alt="pointers"
                                        style="height:10px; width : 10px;" /></div>
                                <div class="">
                                    <h7 class="header">Liquid spills</h7>
                                    <p class="text-muted"><small>Cover the cost of fixing breakdowns caused by liquid
                                            spills, splashes or full immersion.</small></p>
                                </div>
                            </div>
                        </div>
                    </div>
                </b-container>
            </div> -->
        </VueSlickCarousel>
    </main>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
    name: 'NeedSection',
    components: { VueSlickCarousel },
}
</script>

<style scoped>
.header {
    color: #094063;
}

.background {
    background-image: url('@/static/img/rectangle.svg');
    background-repeat: no-repeat;
    background-size: cover;
}
</style>
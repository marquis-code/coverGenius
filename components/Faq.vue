<template>
    <main class="background mt-5">
        <b-container class="py-5">
            <b-row class="d-flex justify-content-between align-items-center pt-5">
                <b-col cols="6" class="pr-5">
                    <h3 class="header text-wrap font-weight-bold pb-5" style="width : 20rem;">We’ve answered questions
                        we get asked the most.</h3>
                    <button class="py-2 px-4 rounded-lg border button"><small class="text-white font-weight-light">Get
                            Started</small></button><small class="text-success px-2">see more questions</small><img
                        src="@/static/img/arrow.svg" alt="" />
                </b-col>
                <b-col cols="6" class="">
                    <b-col class="faqBg border-bottom p-3">
                        <div class="d-flex justify-content-between align-items-center">
                            <h6 style="font-size: small;">Are you an Insurance Comapany?</h6>
                            <div>
                                <img src="@/static/img/toggleArrowOpen.svg" v-if="show" alt="" style="cursor:pointer"
                                    @click.prevent="show = !show" />
                                <img src="@/static/img/toggleArrowClose.svg" v-else alt="" style="cursor:pointer"
                                    @click.prevent="show = !show" />
                            </div>
                        </div>
                        <p v-if="show" class="text-muted py-2 font-weight-light text-wrap"
                            style="width : 26rem; font-size: smaller;">MyCover.ai is a product of the first
                            insurtech in Nigeria. We enable any business to access multiple insurance companies and
                            their products from one place.</p>
                    </b-col>
                    <b-col class="border-bottom p-3">
                        <div class="d-flex justify-content-between align-items-center">
                            <h6 style="font-size: small;">How do I handle claims?</h6>
                            <div><img src="@/static/img/toggleArrowClose.svg" alt="" style="cursor:pointer"
                             /></div>
                        </div>
                    </b-col>
                    <b-col class="border-bottom p-3">
                        <div class="d-flex justify-content-between align-items-center">
                            <h6 style="font-size: small;">Do I need to have an online platform?</h6>
                            <div><img src="@/static/img/toggleArrowClose.svg" alt="" style="cursor:pointer"
                                /></div>
                        </div>
                    </b-col>
                    <b-col class="border-bottom p-3">
                        <div class="d-flex justify-content-between align-items-center">
                            <h6 style="font-size: small;">Do I need a license?</h6>
                            <div><img src="@/static/img/toggleArrowClose.svg" alt="" style="cursor:pointer"
                                 /></div>
                        </div>
                    </b-col>
                </b-col>
            </b-row>
        </b-container>
    </main>
</template>

<script>
export default {
    data() {
        return {
            show: false,
        }
    }
}
</script>

<style scoped>
.header {
    color: #094063;
}

.button {
    background-color: #439687;
}

.background {
    background-image: url('@/static/img/rectangle.svg');
    background-repeat: no-repeat;
    background-size: cover;
}

.faqBg {
    background-color: #E6F4F2;
    box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.18);
}
</style>
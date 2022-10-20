<template>
    <main class="">
            <!-- <div>
                <b-container
                    class="background p-5 d-block d-lg-flex justify-content-between align-items-center rounded-lg border my-5">
                    <div>
                        <h4 class="header text-wrap font-weight-bold text-white mb-5" style="width : 30rem;">Our
                            delivery cover enables you to boost profits, and give you peace of mind while you move
                            packages.</h4>
                        <button class="py-2 px-4 rounded-lg border button mt-4"><small
                                class="text-white font-weight-light">Get Delivery
                                Cover</small></button>
                    </div>
                    <div class="pl-lg-5 d-md-flex justify-content-center align-items-center">
                        <img src="@/static/img/imageGroup1.svg" alt="" class="groupPhoto" />
                    </div>
                </b-container>
            </div>

            <div>
                <b-container
                    class="background p-5 d-block d-lg-flex justify-content-between align-items-center rounded-lg border my-5">
                    <div>
                        <h4 class="header text-wrap font-weight-bold text-white mb-5" style="width : 30rem;">Get Auto
                            Insurance that fits your business needs and budget</h4>
                        <button class="py-2 px-4 rounded-lg border button mt-4"><small
                                class="text-white font-weight-light">Get Auto
                                Insurance</small></button>
                    </div>
                    <div>
                        <div class="pl-lg-5 d-lg-flex justify-content-center align-items-center">
                            <img src="@/static/img/imageGroup2.svg" alt="" class="groupPhoto" />
                        </div>
                    </div>
                </b-container>
            </div> -->

            <div>
                <b-container
                    class="background girlContainer p-5 d-block d-lg-flex justify-content-between align-items-center rounded-lg border my-5">
                    <div>
                        <h4 class="header text-wrap font-weight-bold text-white mb-5" style="width : 30rem;">Imagine not
                            having to pay a  dime everytime your phone or laptop screen gets damaged. Yes, tha’s what
                            Gadget Cover does for you</h4>
                        <button class="py-2 px-4 rounded-lg border button mt-4"><small
                                class="text-white font-weight-light">Get Gadgets Cover</small></button>
                    </div>
                    <div>
                        <div class="">
                            <img src="@/static/img/girl.svg" alt="" class="girl pl-1" />
                        </div>
                    </div>
                </b-container>
            </div>
    </main>
</template>

<script>
export default {
    name: 'AutoInsurance',
}
</script>

<style scoped>
.button {
    background-color: #439687;
}

.header {
    color: #094063;
}

.background {
    background-color: #101828;
}

/* img{
    height: 45%;
    width : 45%;
} */

.image1 {
    height: 40%;
    width: 40%;
}

.girl {
    position: absolute;
    bottom: 0px;
    right:10px;
    height: 300px;
    width: 300px;
}

.girlContainer {
    position: relative
}

.groupPhoto {
    height: 300px;
    width: 300px;
}
</style>

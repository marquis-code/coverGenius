<template>
    <main class="background mt-5">
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
    </main>
</template>

<script>
export default {
    name: 'NeedSection',
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

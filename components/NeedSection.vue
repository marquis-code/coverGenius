<template>
    <main class="background mt-5">
        <b-container class="py-5">
            <div class="d-flex justify-content-between align-items-center pt-5">
                <div class="pr-5">
                    <p class="text-success font-weight-light pb-4">What is covered in Auto Insurance?</p>
                    <h1 class="header text-wrap font-weight-bold" style="width : 20rem;">One solution for your vehicle
                        needs</h1>
                    <p class="text-muted">All the protection you need is right here, so you can drive growth in your
                        business.</p>
                </div>
                <div class="pl-5">
                    <div class="d-flex align-items-start">
                        <div class="pr-3"><img src="@/static/img/ellipse1.svg" alt="pointers"
                                style="height:10px; width : 10px;" /></div>
                        <div class="">
                            <h7 class="header">Vehicle damages</h7>
                            <p class="text-muted"><small> cover financial losses due to accidental damages to your
                                    company’s assets during transit.</small></p>
                        </div>
                    </div>
                    <div class="d-flex align-items-start">
                        <div class="pr-3"><img src="@/static/img/ellipse2.svg" alt="pointers"
                                style="height:10px; width : 10px;" /></div>
                        <div class="">
                            <h7 class="header">Third-party wahala</h7>
                            <p class="text-muted"><small>Our policies save face and keep you worry-free when there are
                                    accidental damages to other vehicles or their riders.</small></p>
                        </div>
                    </div>
                    <div class="d-flex align-items-start">
                        <div class="pr-3"><img src="@/static/img/ellipse3.svg" alt="pointers"
                                style="height:10px; width : 10px;" /></div>
                        <div class="">
                            <h7 class="header">Bodily Injuries</h7>
                            <p class="text-muted"><small> also compensate for damages to riders and drivers involved to
                                    keep business running smoothly.</small></p>
                        </div>
                    </div>
                </div>
            </div>
        </b-container>
    </main>
</template>

<script>
export default {

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
<template>
    <b-aspect aspect="16:9" class="background1 d-flex justify-content-between align-items-center">
        <b-container class="d-flex justify-content-between align-items-center mt-5 h-50">
            <div class="">
                <p class="text-success font-weight-light">Why Auto Insurance?</p>
                <h1 class="header text-wrap font-weight-bold" style="width : 25rem;">Your vehicle's care is our
                    business</h1>
                <p class="text-muted py-2 font-weight-light text-size-small text-wrap" style="width : 25rem;">Setting up
                    any business is not an easy feat, coupled with the
                    risks that come with managing vehicles. Our comprehensive insurance
                    plan gives you complete coverage for your vehicles you covered.
                </p>
            </div>
            <div class="background2 d-flex justify-content-center align-items-center p-2">
                  <img src="@/static/img/animatedCar.svg" alt="" class="border-t-red" />
            </div>
        </b-container>
    </b-aspect >
</template>

<script>
export default {

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
</style>
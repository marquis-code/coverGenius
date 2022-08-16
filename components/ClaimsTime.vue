<template>
    <b-aspect aspect="16:9" class="background1 d-flex justify-content-between align-items-center">
        <b-container class="d-flex justify-content-between align-items-center mt-5 h-50 px-5">
            <div class="">
                <p class="text-success font-weight-light">100% Claims Assessments</p>
                <h3 class="header text-wrap font-weight-bold py-5" style="width : 22rem;">Make Claims in <span class="textColor text-white rounded-circle">15</span>minutes, not 2 months</h3>
                <div class="d-flex align-items-center pb-2">
                    <div class="pr-3"><img src="@/static/img/coloredIndicator.svg" alt="" class="image"/></div>
                    <div>
                        <h6 class="pb-0">Report Claim</h6>
                        <small class="text-muted">It all starts with a click. Log in to your dashboard from your device.</small>
                    </div>
                </div>
                 <div class="d-flex align-items-center pb-2">
                    <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image"/></div>
                    <div>
                        <h6 class="text-muted">Take Picture</h6>
                    </div>
                </div>
                 <div class="d-flex align-items-end pb-2">
                    <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image"/></div>
                    <div>
                        <h6 class="text-muted">Estimate damage</h6>
                    </div>
                </div>
                 <div class="d-flex align-items-end">
                    <div class="pr-3"><img src="@/static/img/dottedIndicator.svg" alt="" class="image"/></div>
                    <div>
                        <h6 class="text-muted">Get Paid</h6>
                    </div>
                </div>
            </div>
            <div class="background2 d-flex justify-content-center align-items-end mt-5 p-4">
                  <img src="@/static/img/phone.svg" style="height: 350px; width: 350px" alt="" class="border-t-red pt-5" />
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
    background-image: url('@/static/img/rectangle2.svg');
    background-repeat: no-repeat;
    background-size: cover;
}

.background2 {
    background-image: url('@/static/img/circle.svg');
    background-repeat: no-repeat;
    background-size: cover;
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
</style>
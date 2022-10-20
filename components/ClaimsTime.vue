<template>
  <main>
    <div>
      <b-aspect
        aspect="16:9"
        class="background1 d-flex justify-content-between align-items-center"
      >
        <b-container
          class="
            sectionContainer
            d-block d-lg-flex
            justify-content-between
            align-items-center
            mt-5
            h-50
          "
        >
          <div class="">
            <p class="text-success font-weight-light">
              100% Claims Assessments
            </p>
            <!-- <h3 class="header text-wrap font-weight-bold py-5" style="width : 22rem;">Make Claims in
                                <span class="textColor text-white rounded-circle">15</span>minutes, not 2 months
                            </h3> -->
            <h3
              class="header text-wrap font-weight-bold py-5"
              style="width: 22rem"
            >
              Make Claims with ease
            </h3>
            <div class="d-flex align-items-center pb-2">
              <div class="pr-3">
                <img
                  src="@/static/img/coloredIndicator.svg"
                  alt=""
                  class="image"
                />
              </div>
              <div @click="activeView = 'Report'">
                <h6 class="pb-0">Report Claim</h6>
                <small class="text-muted"
                  >Our digital self-inspection process lets your team report
                  issues in real-time to keep your business running
                  non-stop.</small
                >
              </div>
            </div>
            <div @click="activeView = 'Picture'" class="d-flex align-items-center pb-2">
              <div class="pr-3">
                <img
                  src="@/static/img/dottedIndicator.svg"
                  alt=""
                  class="image"
                />
              </div>
              <div>
                <h6 class="text-muted">Take Picture</h6>
              </div>
            </div>
            <div @click="activeView = 'Estimate'" class="d-flex align-items-end pb-2">
              <div class="pr-3">
                <img
                  src="@/static/img/dottedIndicator.svg"
                  alt=""
                  class="image"
                />
              </div>
              <div>
                <h6 class="text-muted">Estimate damage</h6>
              </div>
            </div>
            <div class="d-flex align-items-end" @click="activeView = 'Paid'">
              <div class="pr-3">
                <img
                  src="@/static/img/dottedIndicator.svg"
                  alt=""
                  class="image"
                />
              </div>
              <div>
                <h6 class="text-muted">Get Paid</h6>
              </div>
            </div>
          </div>
          <div
            class="
              background2
              d-flex
              justify-content-center
              align-items-center align-lg-items-end
              mt-5
              p-4
            "
          >
            <component :is="activeView" />
          </div>
        </b-container>
      </b-aspect>
    </div>
  </main>
</template>

<script>
import Estimate from '@/components/ClaimsSteps/Estimate.vue';
import Paid from '@/components/ClaimsSteps/Paid.vue';
import Picture from '@/components/ClaimsSteps/Picture.vue';
import Report from '@/components/ClaimsSteps/Report.vue';
export default {
  name: "ClaimsTime",
  components : {
    Estimate,
    Paid,
    Picture,
    Report
  },
  data(){
    return {
      activeView : 'Report'
    }
  }
};
</script>

<style scoped>
.background1 {
  background-image: url("@/static/img/rectangle2.svg");
  background-repeat: no-repeat;
  background-size: cover;
}

.background2 {
  background-image: url("@/static/img/circle.svg");
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

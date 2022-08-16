<template>
   <b-container class="mt-5 pt-5">
        <h2 class="header text-center">Hear from other businesses <br /> getting covered</h2>
        <div class="d-flex align-items-center">
            <div class="lessThan"><img src="@/static/img/lessThan.svg" /></div>
            <div class="d-flex align-items-center">
                <div class="quotationContainer">
                    <img src="@/static/img/quotation.svg" class="quotation" />
                    <div><img src="@/static/img/deliveryMan.svg" alt="" class="deliveryMan" /></div>
                </div>
                <div class="">
                      <img src="@/static/img/gigMileLogo.svg" />
                      <p class="text-muted py-2 font-weight-light text-size-small text-wrap" style="width : 23rem;">Our unique solution allows smoother operations which is suitable for every kind of logistic business.</p>
                </div>
            </div>
            <div class="greaterThan pl-5"><img src="@/static/img/greaterThan.svg" /></div>
        </div>
        <div class="d-flex justify-content-center align-items-center pb-5">
            <div>
            <img src="@/static/img/sliderDotColored.svg" />
            <img src="@/static/img/unColoredDot.svg" />
            <img src="@/static/img/unColoredDot.svg" />
            <img src="@/static/img/unColoredDot.svg" />
            </div>
        </div>
  </b-container>
</template>

<script>
export default {

}
</script>

<style scoped>
      .header {
    color: #094063;
   }

   .quotationContainer {
       position: relative;
   }


   .quotation {
     position: absolute;
     top: 20px;
     left : 32px;
     height: 15%;
     width: 15%;
   }

   .deliveryMan {
     height: 90%;
     width: 90%;
   }
   
   .greaterThan {
     height: 20%;
     width: 20%;
   }
</style>>
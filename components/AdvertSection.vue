<template>
   <b-container class="pt-5 d-flex justify-content-between align-items-center">
       <div class="pr-5">
          <h3 class="header text-wrap font-weight-bold" style="width : 18rem;">Paper-less Insurance for your business</h3>
          <p class="text-muted"><small>Our web interface enables you to conveniently manage your vehicles and riders under the plan. It also empowers you with data to make better management decisions.</small></p>
          <div>
              <div class="border rounded-lg shadow-sm d-flex align-items-center indicator">
                 <img src="@/static/img/firstSidePointer.svg" class="pr-3" style="height:40px" alt="" />
                 <p class="hover:text-black text-muted pt-3"><small>Track Claims</small></p>
              </div>

              <div class="border rounded-lg shadow-sm d-flex align-items-center indicator my-2">
                 <img src="@/static/img/secondSidePointer.svg" class="pr-3" style="height:40px" alt=""                                 />
                 <p class="hover:text-black text-muted pt-3"><small>Manage your Analytics</small></p>
              </div>

              <div class="border rounded-lg shadow-sm d-flex align-items-center indicator">
                 <img src="@/static/img/thirdSidePointer.svg" class="pr-3" style="height:40px" alt="" />
                 <small class="text-xs">Access your insurance plans</small>
              </div>
          </div>
       </div>
       <div class="pl-5">
         <img src="@/static/img/claim.svg" alt="claims" />
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

   /* img {
    height: 30px;
   } */

   .indicator {
    height: 40px;
   }

</style>
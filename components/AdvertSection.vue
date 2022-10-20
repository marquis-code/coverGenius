<template>
  <main class="container mx-auto pt-24">
    <p class="text-green-500 pb-16">Bespoke solutions</p>
    <h3 class="header flex justify-center items-center text-4xl font-extrabold lg:w-4/12 pb-4">
      One-in-all Solution for Businesses
    </h3>
    <div class="lg:flex justify-between space-y-6  lg:space-y-0">
      <div class="flex flex-col justify-between">
        <p class="text-sm lg:w-7/12 header  lg:text-start">
          If a staff leaves, no worries! Seamlessly re-assign their plan to new
          staff from your dashboard. You can also;
        </p>
        <div class="space-y-4 flex justify-between lg:space-x-0 space-x-5 lg:justify-start lg:flex-col py-10 lg:py-0">
          <div class="flex">
            <div class="h-14 w-1 indicator1"></div>
            <div
            @click="activeView = 'Plans'"
              class="
              cursor-pointer
                lg:w-6/12
                w-full
                bg-white
                shadow-md
                py-3
                pl-3
                pt-2
                rounded-r-md
                shadow-gray-400
                pr-10
                lg:pr-0
              "
            >
              Plans
            </div>
          </div>

          <div class="flex">
            <div class="h-14 w-1 indicator2"></div>
            <div
              @click="activeView = 'Claims'"
              class="
              cursor-pointer
                lg:w-6/12
                w-full
                bg-white
                shadow-md
                py-3
                pl-3
                pt-2
                rounded-r-md
                shadow-gray-400
                opacity-25
                pr-10
                lg:pr-0
              "
            >
              Claims
            </div>
          </div>

          <div class="flex">
            <div class="h-14 w-1 indicator3"></div>
            <div
              @click="activeView = 'Beneficiaries'"
              class="
              cursor-pointer
                w-6/12
                bg-white
                shadow-md
                py-3
                pl-3
                pt-2
                rounded-r-md
                shadow-gray-400
                opacity-25
                pr-28
                lg:pr-0
              "
            >
              Beneficiaries
            </div>
          </div>

          <div class="lg:flex hidden">
            <div class="h-14 w-1 indicator4"></div>
            <div
              @click="activeView = 'Wallet'"
              class="
              cursor-pointer
                w-6/12
                bg-white
                shadow-md
                py-3
                pl-3
                pt-2
                rounded-r-md
                shadow-gray-400
                opacity-25
              "
            >
              Wallet
            </div>
          </div>
        </div>
      </div>

      <div class="background space-y-4 pt-3">
        <div class="flex lg:pl-16">
          <div class="flex items-center space-x-2">
            <p class="h-3 w-3 bg-green-800 rounded-full"></p>
            <p class="text-green-400 lg:text-sm text-xs">
              A host of innovative plans for every aspect of your business
            </p>
          </div>
        </div>
        <div>
          <!-- <img
            class="object-cover"
            src="@/static/img/dashboard.svg"
            alt="claims"
          /> -->
          <component :is="activeView" />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import Plans from '@/components/SolutionSteps/Plans.vue';
import Claims from '@/components/SolutionSteps/Claims.vue';
import Beneficiaries from '@/components/SolutionSteps/Beneficiaries.vue';
import Wallet from '@/components/SolutionSteps/Wallet.vue';
export default {
  name: "AdvertSection",
  components : {
    Plans,
    Claims,
    Beneficiaries,
    Wallet
  },
  data(){
    return {
       activeView : 'Plans'
    }
  }
};
</script>

<style scoped>
.header {
  color: #094063;
}

.indicator1 {
  background-color: rgb(154, 81, 206);
}

.indicator2 {
  background-color: rgb(217, 73, 73);
}

.indicator3 {
  background-color: lightskyblue;
}

.indicator4 {
  background-color: #a6f4c5;
}

.background {
  background-color: #f8fcfb;
}
</style>

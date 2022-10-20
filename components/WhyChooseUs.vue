<template>
  <main class="container mx-auto my-10">
    <div>
      <div class="space-y-20 pt-20">
        <div class="flex justify-center items-center flex-col space-y-5">
          <h1 class="header font-extrabold text-3xl lg:w-8/12  text-center">
            Experience all-around insurance for SME, startup or large business.
          </h1>
          <p class="text-center text-sm lg:text-lg text-gray-500 font-light">
            We enable every kind business grow with genuine insurance coverage.
          </p>
        </div>
        <div
          class="w-10/12 mx-auto lg:flex justify-between items-center lg:space-x-16 space-y-7 lg:space-y-0"
        >
          <div class="">
            <img src="@/static/img/affordable.svg" alt="icon" class="pb-4" />
            <h5 class="font-medium text-lg pt-3">Affordable</h5>
              <p class="header font-light text-sm pt-2"
                >Get affordable insurance coverage that fits your budget.</p
              >
          </div>

          <div class="font-medium">
            <img src="@/static/img/paper.svg" alt="icon" class="pb-4" />
            <h5 class=" pt-3 text-lg font-medium">No Paperwork</h5>
              <p class="header font-light text-sm pt-2"
                >We are online! Get your business covered without leaving your
                home or filling out long forms.</p
              >
          </div>

          <div class="font-medium">
            <img src="@/static/img/support.svg" alt="icon" class="pb-4" />
            <h5 class=" pt-3 text-lg font-medium">Added Business Value</h5>
              <p class="header font-light text-sm pt-2"
                >Focus on your KPIs while we worry about your business risks and
                your staff.</p
              >

          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "WhyChoseUs",
};
</script>

<style scoped>
.header {
  color: #094063;
}
</style>

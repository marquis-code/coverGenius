<template>
  <main class="lg:pt-6 container mx-auto my-5 lg:my-16">
    <div class="lg:flex justify-between items-center space-y-10 lg:space-y-0">
      <div class="space-y-3">
        <h3 class="header font-extrabold text-4xl lg:text-5xl">
          Set your business up for success with seamless insurance
        </h3>
        <p class="text-sm lg:text-lg font-light">
          We protect all your hard work with affordable insurance to help your
          business recover from unplanned events quickly.
        </p>
        <div class="pt-3 lg:pt-5">
          <button
            class="
              button
              p-2
              w-4/12
              rounded-md
              text-white
              lg:py-3
              font-light
            "
          >
            Get Covered
          </button>
        </div>
      </div>
      <div class="w-full justify-end flex p-0">
        <img class="" src="@/static/img/rotator.svg" />
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "Introduction",
};
</script>

<style scoped>
.button {
  background-color: #439687;
}

.header {
  color: #094063;
}
</style>

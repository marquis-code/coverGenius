<template>
  <main class="lg:pt-6 container mx-auto my-5 lg:my-16">
    <div class="lg:flex justify-between items-center space-y-10 lg:space-y-0">
      <div class="space-y-3">
        <h3 class="header font-extrabold text-4xl lg:text-5xl lg:w-1/2">
          Set your business up for success with seamless insurance
        </h3>
        <p class="text-sm lg:w-1/2 font-light">
          We protect all your hard work with affordable insurance to help your
          business recover from unplanned events quickly.
        </p>
        <div class="pt-3 lg:pt-5">
          <button
            class="
              button
              p-3
              w-6/12
              lg:w-2/12
              rounded-md
              text-white
              lg:py-3
              font-light
              text-sm
            "
          >
            Get Covered
          </button>
        </div>
      </div>
      <div>
        <img src="@/static/img/rotator.svg" />
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

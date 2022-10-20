<template>
  <main
    class="
     my-9
      background
      container
      mx-auto
      space-y-10
      lg:space-y-0 lg:px-14
      pt-6
      pb-4
      rounded-md
    "
  >
    <p class="text-green-900">Get insurance at your convenience</p>
    <div class="space-y-5 pt-14">
      <h1 class="text-3xl text-white font-bold lg:w-8/12">
        Get your business covered from anywhere
      </h1>
      <p class="text-gray-400 text-sm lg:w-5/12">
        MyCoverGenius is making insurance in Nigeria affordable, easy and
        accessible to everyone. Get covered from any of our multiple sales
        channels.
      </p>
    </div>
    <div class="lg:flex justify-between items-center space-y-14 lg:space-y-0">
      <div class="space-y-10">
        <div class="space-x-3 flex justify-start items-start">
          <div><img src="@/static/img/business.svg" /></div>
          <div class="space-y-3">
            <h1 class="font-bold text-xl text-gray-400">Via our Web Portal</h1>
            <p class="text-gray-400 lg:w-8/12 text-sm">
              Conveniently manage all your business plans and staff from our web
              portal.
            </p>
            <div class="flex items-center space-x-2">
              <p class="text-green-900">Get covered now</p>
              <img src="@/static/img/arrow.svg" />
            </div>
          </div>
        </div>

        <div class="space-x-3 flex justify-start items-start">
          <div><img src="@/static/img/staffs.svg" /></div>
          <div class="space-y-3">
            <h1 class="font-bold text-xl text-gray-400">Via our Mobile App</h1>
            <p class="text-gray-400 lg:w-8/12 text-sm">
              Your staff also enjoys the coverage from our user-friendly mobile
              app.
            </p>
            <div class="flex items-center space-x-2">
              <p class="text-green-900">See the App</p>
              <img src="@/static/img/arrow.svg" />
            </div>
          </div>
        </div>
      </div>
      <div>
        <img src="@/static/img/group.svg" />
      </div>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style>
.background {
  background-color: #101828;
}
</style>

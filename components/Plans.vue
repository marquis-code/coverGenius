<template>
  <main class="container mx-auto">
    <div class="space-y-10">
      <div class="pt-5 flex justify-center items-center flex-col">
        <p class="font-weight-light text-lg py-5 text-green-500 text-center">
          Bespoke plans
        </p>
        <h1
          class="
            header
            pb-3
            text-3xl
            lg:text-5xl
            font-extrabold
            lg:w-8/12
            text-center
          "
        >
          Tailor-made plans suited for your business.
        </h1>
        <p class="text-center text-muted">
          We offer flexible and innovative insurance coverage for every aspect
          of your business.
        </p>
      </div>

      <div class="flex items-center lg:w-4/12 mx-auto space-x-7">
        <div
          @click="activeView = 'Auto'"
          to="#"
          class="rounded-md bg-teal-600 text-white p-1 w-1/2 text-center"
        >
          Auto
        </div>
        <div
          @click="activeView = 'Health'"
          to="#"
          class="
            rounded-md
            text-gray-300
            bg-gray-50
            p-1
            w-1/2
            text-center
            hover:bg-teal-600 hover:text-white
          "
        >
          Health
        </div>
        <div
          @click="activeView = 'Others'"
          to="#"
          class="
            rounded-md
            text-gray-300
            bg-gray-50
            p-1
            w-1/2
            text-center
            hover:bg-teal-600 hover:text-white
          "
        >
          Others
        </div>
      </div>
    </div>

    <div class="w-10/12 mx-auto">
      <component :is="activeView" />
    </div>
  </main>
</template>

<script>
import Auto from "@/components/TailorPlans/Auto.vue";
import Health from "@/components/TailorPlans/Health.vue";
import Others from "@/components/TailorPlans/Others.vue";

export default {
  name: "Plans",
  components: {
    Auto,
    Health,
    Others,
  },
  data() {
    return {
      activeView: "Auto",
    };
  },
};
</script>

<style scoped>
.header {
  color: #094063;
}
</style>

<template>
  <main
    class="background lg:flex justify-between items-start container mx-auto py-28 pt-16 space-y-10 lg:space-y-0 mt-20"
  >
    <div class="lg:w-6/12 space-y-4">
      <h1 class="text-3xl font-extrabold lg:w-1/2" style="color: #439687">
        What would you like to know?
      </h1>
      <div class="flex space-x-4">
        <a
          class="
          bgColor
            group
            relative
            inline-block
            overflow-hidden
            border border-indigo-600
            px-9
            py-2
            rounded-md
            focus:outline-none focus:ring
          "
          href="/download"
        >
          <span
            class="
              absolute
              inset-x-0
              top-0
              h-[2px]
              bg-indigo-600
              transition-all
              group-hover:h-full
              group-active:bg-indigo-500
            "
          ></span>

          <span
            class="
              relative
              text-sm
              font-medium
              transition-colors
              text-white
              group-hover:text-white
            "
          >
            Let's talk
          </span>
        </a>

        <!-- <button class="bgColor text-white text-sm rounded-md px-9 py-2">
          Let's talk
        </button> -->
        <button class="text-green-500 ring-1 ring-gray-50 rounded-md">
          Get Started
        </button>
      </div>
    </div>

    <div class="lg:w-6/12 grid grid-cols-1 divide-y">
      <div class="py-4" :class="[faq1 ? 'bg-green-50' : '']">
        <div class="flex justify-between items-center px-4">
          <h1 class="header font-medium">Are you an insurance company?</h1>
          <img
            src="@/static/img/toggleArrowOpen.svg"
            v-if="faq1"
            alt=""
            style="cursor: pointer"
            @click.prevent="faq1 = !faq1"
          />
          <img
            src="@/static/img/toggleArrowClose.svg"
            v-else
            alt=""
            style="cursor: pointer"
            @click.prevent="faq1 = !faq1"
          />
        </div>
        <div v-if="faq1">
          <p v-if="faq1" class="text-muted pl-6 font-light py-3">
            Mycovergenius is Africa's first and leading insurtech platform. We
            are focused on expanding insurance adoption in Africa by creating
            unique and relevant products for anyone.
          </p>
        </div>
      </div>

      <div class="py-4" :class="[faq2 ? 'bg-green-50' : '']">
        <div class="flex justify-between items-center px-4">
          <h1 class="header font-medium">
            How long before my plan becomes active?
          </h1>
          <img
            src="@/static/img/toggleArrowOpen.svg"
            v-if="faq2"
            alt=""
            style="cursor: pointer"
            @click.prevent="faq2 = !faq2"
          />
          <img
            src="@/static/img/toggleArrowClose.svg"
            v-else
            alt=""
            style="cursor: pointer"
            @click.prevent="faq2 = !faq2"
          />
        </div>
        <div v-if="faq2">
          <p v-if="faq2" class="text-muted pl-6 font-light py-3">
            In the blink of an eye. Like, literally. Get covered right from your
            device. With mycovergenius, you dont have to fill out long forms or
            worry about carrying papers about or visiting any office.
          </p>
        </div>
      </div>

      <div class="py-4" :class="[faq3 ? 'bg-green-50' : '']">
        <div class="flex justify-between items-center px-4">
          <h1 class="header font-medium">How do I get covered?</h1>
          <img
            src="@/static/img/toggleArrowOpen.svg"
            v-if="faq3"
            alt=""
            style="cursor: pointer"
            @click.prevent="faq3 = !faq3"
          />
          <img
            src="@/static/img/toggleArrowClose.svg"
            v-else
            alt=""
            style="cursor: pointer"
            @click.prevent="faq3 = !faq3"
          />
        </div>
        <div v-if="faq3">
          <p v-if="faq3" class="text-muted pl-6 font-light py-3">
            It's easy as having a conversation. Choose a plan that suits your
            business, tell us a bit about your business, complete payment and
            get an insurance certificate immediatly. No paper work is involved.
          </p>
        </div>
      </div>

      <div class="py-4" :class="[faq4 ? 'bg-green-50' : '']">
        <div class="flex justify-between items-center px-4">
          <h1 class="header font-medium">
            Can I get a unique plan for my business?
          </h1>
          <img
            src="@/static/img/toggleArrowOpen.svg"
            v-if="faq4"
            alt=""
            style="cursor: pointer"
            @click.prevent="faq4 = !faq4"
          />
          <img
            src="@/static/img/toggleArrowClose.svg"
            v-else
            alt=""
            style="cursor: pointer"
            @click.prevent="faq4 = !faq4"
          />
        </div>
        <div v-if="faq4">
          <p v-if="faq4" class="text-muted pl-6 font-light py-3">
            Certainly! Thats what we do at mycovergenius. We create tailor-made
            insurance plans to suit your specific business needs.
          </p>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  data() {
    return {
      faq1: false,
      faq2: false,
      faq3: false,
      faq4: false,
    };
  },
};
</script>

<style scoped>
.header {
  color: #094063;
}

.button {
  background-color: #439687;
}

.background {
  background-color: #f8fcfb;
}

.faqBg {
  background-color: #e6f4f2;
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.18);
}

.bgColor {
  background-color: #439687;
}

.header {
  color: #094063;
}
</style>

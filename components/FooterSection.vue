<template>
  <main class="container mx-auto pt-16">
    <div class="pr-5 py-5"><img src="@/static/img/logo.svg" alt="logo" /></div>
    <!-- <section class="grid lg:grid-cols-5 gap-6 md:grid-cols-3 grid-cols-2"> -->
    <section class="flex justify-between items-start flex-wrap">
      <section class="space-y-6 hidden lg:block">
        <div class="flex items-center space-x-2">
          <p class="font-medium">Office</p>
          <p class="font-light">
            8, Province Estate, Maruwa Bus-Stop, Lekki Phase 1
          </p>
        </div>
        <div class="flex items-center space-x-2">
          <p class="font-medium">Email</p>
          <p class="font-light">hello@mycovergenius.com</p>
        </div>
        <div class="flex items-center space-x-2">
          <p class="font-medium">Phone</p>
          <p class="font-light">+234 8099988005</p>
        </div>
        <div class="flex space-x-5 items-center">
          <img src="@/static/img/facebook.svg" />
          <img src="@/static/img/instagram.svg" />
          <img src="@/static/img/linkedin.svg" />
          <img src="@/static/img/twitter.svg" />
        </div>
      </section>
      <section class="space-y-6">
        <h5 class="font-bold text-lg">Quick Links</h5>
        <p><router-link to="#" class="font-light">Home</router-link></p>
        <p><router-link to="#" class="font-light">FAQs</router-link></p>
        <p>
          <router-link to="#" class="font-light">Sign Up/ Login</router-link>
        </p>
        <p><router-link to="#" class="font-light">News</router-link></p>
      </section>
      <section class="space-y-6">
        <h5 class="font-bold">Products</h5>
        <p><router-link to="#" class="font-light">Health Cover</router-link></p>
        <p><router-link to="#" class="font-light">Auto Cover</router-link></p>
        <p><router-link to="#" class="font-light">Travel Cover</router-link></p>
        <p><router-link to="#" class="font-light">Gadget Cover</router-link></p>
        <p><router-link to="#" class="font-light">Office Cover</router-link></p>
        <p>
          <router-link to="#" class="font-light">Delivery Cover</router-link>
        </p>
      </section>
      <section class="space-y-6">
        <h5 class="font-bold text-lg">Company</h5>
        <p><router-link to="#" class="font-light">About Us</router-link></p>
        <p><router-link to="#" class="font-light">Resources</router-link></p>
        <p>
          <router-link to="#" class="font-light">Foe Individuals</router-link>
        </p>
        <p><router-link to="#" class="font-light">API</router-link></p>
      </section>
      <section class="space-y-6">
        <h5 class="font-bold text-lg">Legal</h5>
        <p>
          <router-link to="#" class="font-light">Privacy Policy</router-link>
        </p>
        <p>
          <router-link to="#" class="font-light">Cookie Policy</router-link>
        </p>
        <p>
          <router-link to="#" class="font-light"
            >Terms & Conditions</router-link
          >
        </p>
      </section>
      <section class="space-y-6 lg:hidden">
        <div class="flex items-center space-x-2 space-y-5">
          <p class="font-medium">Office</p>
          <p class="">8, Province Estate, Maruwa Bus-Stop, Lekki Phase 1</p>
        </div>
        <div class="flex items-center space-x-2 space-y-5">
          <p class="font-medium">Email</p>
          <p class="">hello@mycovergenius.com</p>
        </div>
        <div class="flex items-center space-x-2 space-y-5">
          <p class="font-medium">Phone</p>
          <p class="">+234 8099988005</p>
        </div>
        <div class="flex space-x-5 items-center">
          <img src="@/static/img/facebook.svg" />
          <img src="@/static/img/instagram.svg" />
          <img src="@/static/img/linkedin.svg" />
          <img src="@/static/img/twitter.svg" />
        </div>
      </section>
    </section>
    <p style="font-size: small" class="text-muted pt-5">
      mycovergenius © 2021 / ALL RIGHTS RESERVED
    </p>
  </main>
</template>

<script>
export default {};
</script>

<style scoped>
.button {
  background-color: #439687;
}

.header {
  color: #094063;
}

h5 {
  color: #344054;
}

p {
  color: #344054;
}
</style>

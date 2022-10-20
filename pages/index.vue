<template>
  <main class="w-full">
    <Navbar />
    <Introduction />
    <Brands />
    <hr />
    <WhyChooseUs />

    <AdvertSection />

    <Plans />
    <ClaimsTime />

    <InsuranceCover />
    <Partners />
    <Faq />
    <FooterSection />
    <!--  -->
  </main>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import Introduction from "../components/Introduction.vue";
import Brands from "../components/Brands.vue";
import WhyChooseUs from "../components/WhyChooseUs.vue";
import AdvertSection from "../components/AdvertSection.vue";
import Plans from "../components/Plans.vue";
import InsuranceCover from "../components/InsuranceCover.vue";
import Partners from "../components/Partners.vue";
import Faq from "../components/Faq.vue";
import FooterSection from "../components/FooterSection.vue";

export default {
  name: "IndexPage",
  components: {
    Navbar,
    Introduction,
    Partners,
    Brands,
    WhyChooseUs,
    AdvertSection,
    Faq,
    FooterSection,
    Plans,
    Partners,
    InsuranceCover,
  },
};
</script>

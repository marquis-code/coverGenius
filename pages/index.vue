<template>
    <main>
        <Navbar />
            <Introduction />
            <Brands />
            <Insurance />
            <WhyChooseUs />
            <NeedSection />
            <AdvertSection />
            <ClaimsTime />
            <AutoInsurance />
            <BussinessCovered />
            <Faq />
            <FooterSection />
    </main>
</template>

<script>
import Navbar from '../components/Navbar.vue';
import Introduction from '../components/Introduction.vue';
import Brands from '../components/Brands.vue';
import Insurance from '../components/Insurance.vue';
import WhyChooseUs from '../components/WhyChooseUs.vue';
import NeedSection from '../components/NeedSection.vue';
import AdvertSection from '../components/AdvertSection.vue';
import ClaimsTime from '../components/ClaimsTime.vue';
import AutoInsurance from '../components/AutoInsurance.vue';
import BussinessCovered from '../components/BussinessCovered.vue';
import Faq from '../components/Faq.vue';
import FooterSection from '../components/FooterSection.vue';
export default {
    name: "IndexPage",
    components: { Navbar, Introduction, Brands, Insurance, WhyChooseUs, NeedSection, AdvertSection, ClaimsTime, AutoInsurance, BussinessCovered, Faq, FooterSection }
}
</script>

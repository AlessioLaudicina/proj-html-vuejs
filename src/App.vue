<script>
import HeaderTop from './components/HeaderTop.vue';
import HeaderBottom from './components/HeaderBottom.vue';
import FloatSection from './components/Floatsection.vue';
import BrandSection from './components/BrandSection.vue';
import CardsSection from './components/CardsSection.vue';
import CtaSection from './components/CtaSection.vue';
import TestimonialSection from './components/TestimonialSection.vue';
import MarketingSection from './components/MarketingSection.vue';
import ContactSection from './components/ContactSection.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    HeaderTop,
    HeaderBottom,
    FloatSection,
    BrandSection,
    CardsSection,
    CtaSection,
    TestimonialSection,
    MarketingSection,
    ContactSection,
    Footer,
  }
}

</script>

<template>
  <header>
    <!--header top -->
    <HeaderTop></HeaderTop>
    <!--header bottom -->
    <HeaderBottom></HeaderBottom>
  </header>


  <main>
    <!-- float section -->
    <FloatSection></FloatSection>
    <!-- brands section -->
    <BrandSection></BrandSection>
    <!-- cards section -->
    <CardsSection></CardsSection>
    <!-- call to action  section -->
    <CtaSection></CtaSection>
    <!-- awards section -->
    <!-- testimonial section -->
    <TestimonialSection></TestimonialSection>
    <!-- marketing resources section -->
    <MarketingSection></MarketingSection>
    <!-- contact  section -->
    <ContactSection></ContactSection>

  </main>

  <footer>
    <!-- footer top -->
    <Footer></Footer>
    <!-- footer bottom -->
  </footer>
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
</style>

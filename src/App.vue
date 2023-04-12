<script>
import HeaderTop from './components/HeaderTop.vue';
import HeaderBottom from './components/HeaderBottom.vue';
import FloatSection from './components/Floatsection.vue';
import BrandSection from './components/BrandSection.vue';
import CardsSection from './components/CardsSection.vue';
import CtaSection from './components/CtaSection.vue';
export default {
  name: 'App',
  components: {
    HeaderTop,
    HeaderBottom,
    FloatSection,
    BrandSection,
    CardsSection,
    CtaSection,
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
    <!-- marketing resources section -->
    <!-- contact  section -->

  </main>

  <footer>
    <!-- footer top -->
    <!-- footer bottom -->
  </footer>
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
</style>

<script>
import HeaderTop from './components/HeaderTop.vue';
import HeaderBottom from './components/HeaderBottom.vue';
import FloatSection from './components/Floatsection.vue';
import BrandSection from './components/BrandSection.vue';
export default {
  name: 'App',
  components: {
    HeaderTop,
    HeaderBottom,
    FloatSection,
    BrandSection
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
    <!-- call to action  section -->
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

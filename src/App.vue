<script>
import HeaderTop from './components/HeaderTop.vue';
import HeaderBottom from './components/HeaderBottom.vue';
import FloatSection from './components/Floatsection.vue';
export default {
  name: 'App',
  components: {
    HeaderTop,
    HeaderBottom,
    FloatSection
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

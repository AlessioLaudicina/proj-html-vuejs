<script>
import HeaderTop from './components/HeaderTop.vue';
import HeaderBottom from './components/HeaderBottom.vue';
export default {
  name: 'App',
  components: {
    HeaderTop,
    HeaderBottom
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

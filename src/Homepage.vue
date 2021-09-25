<template>
  <div class="homepage">
    <Header logo="Benfit" />
  </div>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'Homepage',
  components: {
    Header
  }
}
</script>

<style lang="scss">
@import 'assets/scss/main.scss';
@import 'assets/scss/global/colors.scss';
@import 'assets/scss/global/fonts.scss';
.homepage {
  display: flex;
}
</style>

<script>
import AppTop from './footer/AppTop.vue';
import AppBottom from './footer/AppBottom.vue';
export default {
  name: 'Footer',
  components: {
    AppTop,
    AppBottom,
  },
};
</script>

<template>
  <footer>
    <AppTop />
    <AppBottom />
  </footer>
</template>

<style scoped lang="scss"></style>

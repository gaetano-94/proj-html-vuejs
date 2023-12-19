<script>
import AppHeaderApertura from './AppHeaderApertura.vue';
import AppHeaderContatti from './AppHeaderContatti.vue';
export default {
  name: 'Header',
  components: {
    AppHeaderApertura,
    AppHeaderContatti,
  },
};
</script>

<template>
  <header>
    <AppHeaderApertura />
    <AppHeaderContatti />
  </header>
</template>

<style scoped lang="scss"></style>

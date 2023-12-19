<script>
import AppApertura from './header/AppApertura.vue';
import AppContatti from './header/AppContatti.vue';
export default {
  name: 'Header',
  components: {
    AppApertura,
    AppContatti,
  },
};
</script>

<template>
  <header>
    <AppApertura />
    <AppContatti />
  </header>
</template>

<style scoped lang="scss"></style>

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
    <div class="container d-flex">
      <AppApertura />
      <AppContatti />
    </div>
  </header>
</template>

<style scoped lang="scss">
header {
  background-color: #21333e;
  max-height: 50px;
  width: 100%;
  position: fixed;
  z-index: 10;

  .container {
    max-width: 1160px;
    height: 100%;
    color: grey;
    justify-content: space-between;
    align-items: center;
    padding-top: 10px;
  }
}
</style>

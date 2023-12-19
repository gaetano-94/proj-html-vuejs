<script>
import AppSezioneUno from './main/AppSezioneUno.vue';
import AppSezioneDue from './main/AppSezioneDue.vue';
import AppSezioneTre from './main/AppSezioneTre.vue';
import AppSezioneQuattro from './main/AppSezioneQuattro.vue';
import AppSezioneCinque from './main/AppSezioneCinque.vue';
import AppSezioneSei from './main/AppSezioneSei.vue';
import AppSezioneSette from './main/AppSezioneSette.vue';

export default {
  name: 'Main',
  components: {
    AppSezioneUno,
    AppSezioneDue,
    AppSezioneTre,
    AppSezioneQuattro,
    AppSezioneCinque,
    AppSezioneSei,
    AppSezioneSette,
  },
};
</script>

<template>
  <main>
    <AppSezioneUno />
    <AppSezioneDue />
    <AppSezioneTre />
    <AppSezioneQuattro />
    <AppSezioneCinque />
    <AppSezioneSei />
    <AppSezioneSette />
  </main>
</template>

<style scoped lang="scss"></style>

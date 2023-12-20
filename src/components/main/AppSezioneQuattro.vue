<script>
export default {
  name: 'SezioneQuattro',
};
</script>

<template>
  <section>
    <div class="container px-0">
      <div class="row px-0">
        <div class="col-2 px-0">
          <img src="../../assets/img/logo-5.png" alt="" />
        </div>
        <div class="col-2 px-0">
          <img src="../../assets/img/logo-1.png" alt="" />
        </div>
        <div class="col-2 px-0">
          <img src="../../assets/img/logo-2.png" alt="" />
        </div>
        <div class="col-2 px-0">
          <img src="../../assets/img/logo-3.png" alt="" />
        </div>
        <div class="col-2 px-0">
          <img src="../../assets/img/logo-4.png" alt="" />
        </div>
        <div class="col-2 px-0">
          <img src="../../assets/img/logo-5.png" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
section {
  height: 290px;
  width: 100%;
  background-color: #eef4ed;

  .container {
    width: 100%;
    margin-left: 30px;
  }

  .row {
    align-items: center;
    flex-wrap: nowrap;
    width: 100%;
    margin: 0% auto;
    padding: 110px;
    gap: 30px;

    .col-2 {
      display: flex;
      justify-content: center;

      img {
        display: block;
        object-fit: cover;
        filter: invert(0.6);
      }
    }
  }
}
</style>

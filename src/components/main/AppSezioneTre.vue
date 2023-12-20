<script>
export default {
  name: 'SezioneTre',
};
</script>

<template>
  <div class="row">
    <div class="col-6 left">
      <div class="gp-container">
        <!-- testo top -->
        <span class="text-uppercase fw-bold pb-3 span-top"
          >Abaout the Network</span
        >
        <div>
          <span class="fs-1 px-2 text-white span-uno"
            ><strong>The</strong></span
          >
          <span class="fs-1 text-white"><strong> Company</strong></span>
        </div>
        <p class="text-white pt-3 fs-6">
          With all of this expertise and capability comes an unrivalled
          commitment to customer service
        </p>
        <!-- /testo top -->
        <div class="row">
          <!-- colonna di sinistra -->
          <div class="col-3">
            <div class="pb-5 gp-div-bg">
              <span class="text-white fs-3"><strong>0%</strong></span>
            </div>
            <div class="pb-5 mt-5 gp-div-bg">
              <span class="text-white fs-3"><strong>0%</strong></span>
            </div>
            <div class="pb-5 mt-5 gp-div-bg">
              <span class="text-white fs-3"><strong>1%</strong></span>
            </div>
          </div>
          <!-- /colonna di sinistra -->
          <!-- colonna di destra con text -->
          <div class="col-9 ps-5 pe-0">
            <div>
              <h3 class="text-white pb-3">Leadership</h3>
              <p class="text-secondary">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              </p>
            </div>
            <div>
              <h3 class="text-white pb-3">Psychology</h3>
              <p class="text-secondary">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              </p>
            </div>
            <div>
              <h3 class="text-white pb-3">Flexibility</h3>
              <p class="text-secondary">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              </p>
            </div>
          </div>
          <!-- /colonna di destra con text -->
        </div>
      </div>
    </div>
    <div class="col-6 right"></div>
  </div>
</template>

<style scoped lang="scss">
.row {
  height: 1000px;

  .gp-div-bg {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    border: 4px solid gray;
    text-align: center;
    padding-top: 15px;
  }

  .left {
    background-color: black;
    height: 100%;

    .gp-container {
      display: flex;
      flex-direction: column;
      width: 400px;
      padding-top: 200px;
      margin: 0 auto;
      padding-left: 50px;

      .span-top {
        color: #00a6a6;
      }

      .span-uno {
        background-color: #0e272d;
      }
    }
  }

  .right {
    background-image: url(../../assets/img/about-5.jpg);
    height: 100%;
    background-position-y: top;
    background-position-x: right;
    background-repeat: no-repeat;
    background-size: cover;
  }
}
</style>

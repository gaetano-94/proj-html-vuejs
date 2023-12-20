<script>
export default {
  name: 'SezioneDue',
};
</script>

<template>
  <section>
    <div class="container">
      <div class="row">
        <div class="col-4">
          <p class="pb-2 text-uppercase p-1">
            <strong>Our Business Areas</strong>
          </p>
          <h3 class="fs-1"><strong>Logistics</strong></h3>
          <h3 class="fs-1"><strong>Services</strong></h3>
          <p class="pt-2 pb-2">
            We are leaders in providing logistics services with a set of cutting
            edge technologies and a team of experienced and renowned
            professionals
          </p>
          <div>
            <button class="me-3 btn btn-bg gp-btn">Tradition</button>
            <button class="me-3 btn btn-bg gp-btn">Quality</button>
            <button class="btn btn-bg gp-btn">Security</button>
          </div>
          <button class="text-uppercase btn mt-4 btn-1">Read More</button>
        </div>
        <div class="col-4 bg-white">
          <div class="pt-5 px-5">
            <img
              src="../../assets/img/gallery-3.jpg"
              alt=""
              class="img-fluid"
            />
            <h3 class="mt-4">Technology</h3>
            <p>
              Focused on developing technology solutions adapted to our client's
              needs.
            </p>
          </div>
        </div>
        <div class="col-4 bg-white">
          <div class="pt-5 px-5">
            <img
              src="../../assets/img/gallery-5.jpg"
              alt=""
              class="img-fluid"
            />
            <h3 class="mt-4">Transport</h3>
            <p>
              We develop operational strategies to improve logistical
              efficiency.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
section {
  background-color: #eef4ed;
  width: 100%;
  height: 725px;

  .container {
    width: 1150px;

    .row {
      padding-top: 120px;
      flex-wrap: nowrap;
      gap: 30px;

      .col-4 {
        height: 450px;
        border-radius: 10px;
      }
      .p-1 {
        color: #00a6a6;
      }

      p {
        color: gray;
        font-size: 20px;
      }
      .btn-bg {
        background-color: #cce3de;
      }

      .gp-btn {
        color: #4595a9;
      }
      .btn-1 {
        background-color: #058283;
        margin-right: 20px;
        color: white;
        padding: 5px 25px;
        border-radius: 3px;
      }
    }
  }
}
</style>

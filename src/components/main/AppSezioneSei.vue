<script>
export default {
  name: 'SezioneSei',
};
</script>

<template>
  <section>
    <div class="container">
      <div class="row">
        <div class="col-6 text-white">
          <p class="text-uppercase text-top">Newsletter</p>
          <span class="fs-1 know fw-bold">Know</span>
          <span class="fs-1 fw-bold"> First</span>
          <p class="mt-4 text-secondary">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sequi
            rerum quos, amet,
          </p>
        </div>
        <div class="col-6 text-white">
          <div class="form-floating mb-3 opacity">
            <input
              type="email"
              class="form-control"
              id="floatingInput"
              placeholder="name@example.com"
            />
            <label for="floatingInput">Name</label>
          </div>
          <div class="form-floating opacity">
            <input
              type="password"
              class="form-control"
              id="floatingPassword"
              placeholder="Password"
            />
            <label for="floatingPassword" class="text-balck">Email</label>
          </div>
          <button class="mt-4 px-4 py-1 text-uppercase text-white btn btn-1">
            Subscribe
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
section {
  height: 450px;
  background-image: url(../../assets/img/bg-1.jpg);
  background-position: center;
  background-size: cover;

  .container {
    max-width: 1150px;

    .row {
      padding-top: 150px;
      padding-left: 100px;
      padding-right: 100px;

      .text-top {
        color: #00a6a6;
      }

      .know {
        background-color: #058283;
        padding: 0px 10px;
      }

      .btn-1 {
        background-color: #058283;
      }

      .opacity {
        filter: opacity(0.6);
        color: gray;
      }
    }
  }
}
</style>

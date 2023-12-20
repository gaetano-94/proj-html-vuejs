<script>
export default {
  name: 'Top',
};
</script>

<template>
  <section>
    <div class="container">
      <div class="row">
        <div class="col-3">
          <div class="d-flex pb-3">
            <div class="fs-4 text-uppercase py-1 nex">Nex</div>
            <div class="fs-4 ps-1 pt-1 text-uppercase gen">Gen</div>
          </div>
          <p class="fs-5 pb-3">
            A Functional HTML Template for Corporate & Business
          </p>
          <ul class="ps-0">
            <li class="pb-3">
              <div>
                <i class="fa-solid fa-phone pe-2" style="color: grey"></i>
                <a href="#" class="pe-3">+1 (305) 1234-5678</a>
              </div>
            </li>
            <li class="pb-3">
              <div>
                <i class="fa-solid fa-envelope pe-2" style="color: grey"></i>
                <a href="#" class="pe-3">hello@example.com</a>
              </div>
            </li>
            <li class="pb-3">
              <div>
                <i
                  class="fa-solid fa-location-dot pe-2"
                  style="color: gray"
                ></i>
                <a href="#" class="pe-3">Main Avenue,987</a>
              </div>
            </li>
          </ul>
          <button class="text-uppercase btn btn-2">Get in Touch</button>
        </div>
        <div
          class="col-3 py-4 d-flex flex-column justify-content-center align-items-center gp-bg"
        >
          <h3 class="pb-3 pe-5">About</h3>
          <ul class="ps-0">
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">The Company</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Institutional</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Social & Events</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Innovation</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Environment</a>
            </li>
            <li>
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Technology</a>
            </li>
          </ul>
        </div>
        <div
          class="col-3 py-4 d-flex flex-column justify-content-center align-items-center gp-bg"
        >
          <h3 class="pb-3 pe-4">Transport</h3>
          <ul class="ps-0">
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Industialized</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Chemicals</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Packaged Liquids</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Construction</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Laminated Wood</a>
            </li>
            <li>
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">And others</a>
            </li>
          </ul>
        </div>
        <div
          class="col-3 py-4 d-flex flex-column justify-content-center align-items-center gp-bg"
        >
          <h3 class="pb-3 pe-4">Support</h3>
          <ul class="ps-0">
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Responsibility</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Terms of Use</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">About Cookies</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Privacy Policy</a>
            </li>
            <li class="pb-1">
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Accessibility</a>
            </li>
            <li>
              <i class="fa-solid fa-chevron-right pe-2" style="color: grey"></i>
              <a href="#">Information</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
section {
  width: 100%;
  height: 620px;
  background-image: url(../../assets/img/bg-10.jpg);
  background-position: left;
  background-position-x: center;

  .container {
    // max-width: 1150px;
    padding-top: 120px;

    .row {
      gap: 20px;
      flex-wrap: nowrap;
    }

    .gp-bg {
      background-color: lightgray;
      filter: opacity(0.5);
      border-radius: 10px;
    }

    .nex {
      background-color: aqua;
      border-radius: 30px 0px 0px 30px;
      padding-left: 40px;
      filter: opacity(0.5);
      color: #058283;
    }

    .gen {
      color: white;
    }

    p {
      color: gray;
    }

    a {
      color: grey;
    }

    .btn-2 {
      border: 1px solid #058283;
      color: white;
      padding: 5px 25px;
    }

    h3 {
      color: white;
    }
  }
}
</style>

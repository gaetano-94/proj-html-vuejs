<script>
export default {
  name: 'SezioneUno',
};
</script>

<template>
  <section>
    <!-- super contenitore -->
    <div class="container-uno">
      <!-- navbar -->
      <div class="d-flex justify-content-between px-3">
        <!-- lato sinistro navbar -->
        <div class="d-flex justify-content-center align-items-center">
          <div class="nex fs-4 text-uppercase py-1">Nex</div>
          <div class="fs-4 ps-1 text-uppercase gen">Gen</div>
        </div>
        <!-- /lato sinistro navbar -->
        <!-- lato destro navbar -->
        <div>
          <ul class="d-flex">
            <li>
              <a href="#" class="px-3 fs-5">Home</a>
            </li>
            <li>
              <a href="#" class="px-3 fs-5">Services</a>
            </li>
            <li>
              <a href="#" class="px-3 fs-5">Skills</a>
            </li>
            <li>
              <a href="#" class="px-3 fs-5">Partners</a>
            </li>
            <li>
              <a href="#" class="px-3 fs-5">Blog</a>
            </li>
            <li class="px-1">
              <a href="#" class="px-3 fs-5">Get in Touch</a>
            </li>
          </ul>
        </div>
        <!-- /lato destro navbar -->
      </div>
      <!-- /navbar -->
      <!-- contenitore bottom -->
      <div>
        <div class="container-due">
          <h1><strong>Logistic that goes further.</strong></h1>
          <p class="fs-4">
            For 20 years working with the most innovative in the field of
            trasport.
          </p>
          <button class="text-uppercase btn btn-1">Get in Touch</button>
          <button class="text-uppercase btn btn-2">Read More</button>
        </div>
      </div>
      <!-- /contenitore bottom -->
    </div>
    <!-- /super contenitore -->
  </section>
</template>

<style scoped lang="scss">
section {
  background-image: url(../../assets/img/jumbo.jpg);
  width: 100%;
  height: 860px;
  background-position: bottom;
  overflow-y: hidden;
  filter: brightness(0.5);
  position: absolute;
  top: 50px;

  .container-uno {
    max-width: 1150px;
    margin: 20px auto;
    position: relative;

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

    a {
      color: white;
      text-transform: uppercase;
      &:hover {
        background-color: #058283;
        padding: 5px;
      }
    }
  }
  .container-due {
    position: absolute;
    top: 150px;
    right: 0;
    width: 400px;
    margin-right: 100px;

    h1 {
      font-size: 90px;
      color: white;
    }

    p {
      color: white;
    }

    .btn-1 {
      background-color: #058283;
      margin-right: 20px;
      color: white;
      padding: 5px 25px;
    }

    .btn-2 {
      border: 1px solid #058283;
      color: white;
      padding: 5px 25px;
    }
  }
}
</style>

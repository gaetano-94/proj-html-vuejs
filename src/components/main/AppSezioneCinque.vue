<script>
export default {
  name: 'SezioneCinque',
};
</script>

<template>
  <section>
    <div class="container px-0">
      <div>
        <span class="text-uppercase span-top"
          ><strong>Our Editorial Content</strong></span
        >
        <div class="my-3">
          <span class="fs-1"><strong>Latest </strong></span>
          <span class="fs-1 news"><strong>News</strong></span>
        </div>
      </div>
      <div class="d-flex justify-content-between align-items-center">
        <p class="fs-5 text-gray">
          Every week we publish content about what is best in the business word.
        </p>
        <button class="btn btn-sell-all mb-2 text-uppercase px-4">
          See All
        </button>
      </div>
      <div class="row mx-0">
        <div class="col-4 box-1">
          <h3 class="text-white text fs-3">
            <strong>Increasing creativity is possible for everyone</strong>
          </h3>
        </div>
        <div class="col-4 box-2">
          <h3 class="text-white text fs-3">
            <strong
              >Because market research is part of the business plan</strong
            >
          </h3>
        </div>
        <div class="col-4 box-3">
          <h3 class="text-white text fs-3">
            <strong>Working from home is now a trend</strong>
          </h3>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
section {
  padding: 130px;
  width: 100%;

  .container {
    width: 100%;
    margin: 0px auto;

    .span-top {
      color: #00a6a6;
    }

    .news {
      background-color: lightgray;
      padding: 0px 10px;
      color: #00a6a6;
      filter: opacity(0.7);
    }

    .text-gray {
      color: gray;
    }

    .btn-sell-all {
      background-color: #00a6a6;
      color: white;
    }

    .row {
      gap: 20px;
      flex-wrap: nowrap;
      width: 100%;

      .col-4 {
        background-color: blue;
        text-align: center;
        height: 400px;
        border-radius: 10px;
        filter: brightness(0.6);
        margin-top: 30px;
        width: 32%;

        .text {
          margin-top: 270px;
          color: white;
        }
      }

      .box-1 {
        background-image: url(../../assets/img/news-1.jpg);
        background-size: cover;
        background-position: center;
      }

      .box-2 {
        background-image: url(../../assets/img/news-2.jpg);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
      }

      .box-3 {
        background-image: url(../../assets/img/news-3.jpg);
        background-size: cover;
        background-position: center;
      }
    }
  }
}
</style>

<template>
  <div>
    <section class="banner-area">
      <div class="image">
        <b-img src="~/../src/assets/images/Hero.png" fluid-grow></b-img>
        <div class="image-content text-white text-center">
          <b-row no-gutters>
            <b-col cols="12" md="10" offset-md="1">
              <b> Nothing can stop you </b>
            </b-col>
          </b-row>

          <b-button variant="light" class="text-danger">
            <b>FIND OUT MORE</b>
          </b-button>
        </div>
      </div>
    </section>
    <section class="featured-products text-center">
      <span class="title"> Featured Products </span>
      <div class="products">swiper</div>
    </section>
    <section class="videos p-5">
      <b-container fluid>
        <b-row>
          <b-col md="4">
            <span class="videos-title">
              Feel the excellent wet braking with Driveways!
            </span></b-col
          >
          <b-col md="3" offset-md="5">
            <b-button variant="light" block class="text-danger">
              WATCH ALL VIDEOS
            </b-button>
          </b-col>
        </b-row>

        <b-row no-gutters>
          <b-col cols="12" lg="9"> </b-col>
          <b-col lg="3" class="d-block d-none"> </b-col>
        </b-row>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  layout: "Default",
};
</script>

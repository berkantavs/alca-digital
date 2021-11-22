<template>
  <div>
    <section class="banner-area">
      <div class="image">
        <b-img src="~/../src/assets/images/hero.png" fluid-grow></b-img>
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
    <section class="videos">
      <b-container fluid>
        <b-row>
          <b-col lg="4" sm="12">
            <span class="videos-title">
              Feel the excellent wet braking with Driveways!
            </span></b-col
          >
          <b-col lg="3" offset-lg="5" class="d-lg-block d-none">
            <b-button variant="light" block class="text-danger">
              WATCH ALL VIDEOS
            </b-button>
          </b-col>
        </b-row>

        <b-row no-gutters>
          <b-col cols="12" lg="9"> </b-col>
          <b-col lg="3" class="d-block d-none"> </b-col>
        </b-row>
        <div class="video-area">
          <iframe
            width="100%"
            class="iframe"
            height="193px"
            src="https://www.youtube.com/embed/JvIRuAW9Maw"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
        <div class="mt-2 d-sm-block d-lg-none">
          <b-button variant="light" block class="text-danger">
            WATCH ALL VIDEOS
          </b-button>
        </div>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  layout: "Default",
};
</script>

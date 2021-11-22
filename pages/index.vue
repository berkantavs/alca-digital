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
      <div class="title">
        <span> Featured Products </span>
      </div>
      <div class="products position-relative">
        <b-row>
          <b-col md="10" offset-md="1">
            <swiper :options="swiperOption" class="swiper">
              <swiper-slide>
                <b-card class="swiper-card" no-body>
                  <b-card-header>
                    <span class="swiper-card-title"> ICEWAYS </span>
                  </b-card-header>
                  <b-card-body>
                    <p class="swiper-card-desc">
                      City life is changing. So are the habits of urban
                      citizens. 4X4 cars that were previously used only on
                      challenging lands are now preferred for urban use.
                    </p>
                    <b-row>
                      <b-col cols="6" lg="6" style="padding-right: 3px">
                        <b-button variant="outline-danger" block>
                          LEARN MORE
                        </b-button>
                      </b-col>
                      <b-col cols="6" lg="6" style="padding-left: 3px">
                        <b-button variant="danger" block>
                          FIND A DEALER
                        </b-button>
                      </b-col>
                    </b-row>
                  </b-card-body>
                </b-card>
              </swiper-slide>
              <swiper-slide>
                <b-card class="swiper-card" no-body>
                  <b-card-header>
                    <span class="swiper-card-title"> Driveways Sport </span>
                  </b-card-header>
                  <b-card-body>
                    <p class="swiper-card-desc">
                      Driveways is a ‘’Comfort tyre’’ developed for a
                      considerably wide vehicle pool ranging from middle class
                      sedans to upper class comfort automobiles.
                    </p>
                    <b-row>
                      <b-col cols="6" lg="6" style="padding-right: 3px">
                        <b-button variant="outline-danger" block>
                          LEARN MORE
                        </b-button>
                      </b-col>
                      <b-col cols="6" lg="6" style="padding-left: 3px">
                        <b-button variant="danger" block>
                          FIND A DEALER
                        </b-button>
                      </b-col>
                    </b-row>
                  </b-card-body>
                </b-card>
              </swiper-slide>
              <swiper-slide>
                <b-card class="swiper-card" no-body>
                  <b-card-header>
                    <span class="swiper-card-title">
                      Driveways COMPETUS H/P
                    </span>
                  </b-card-header>
                  <b-card-body>
                    <p class="swiper-card-desc">
                      City life is changing. So are the habits of urban
                      citizens. 4X4 cars that were previously used only on
                      challenging lands are now preferred for urban use.
                    </p>
                    <b-row>
                      <b-col cols="6" lg="6" style="padding-right: 3px">
                        <b-button variant="outline-danger" block>
                          LEARN MORE
                        </b-button>
                      </b-col>
                      <b-col cols="6" lg="6" style="padding-left: 3px">
                        <b-button variant="danger" block>
                          FIND A DEALER
                        </b-button>
                      </b-col>
                    </b-row>
                  </b-card-body>
                </b-card>
              </swiper-slide>
              <swiper-slide>
                <b-card class="swiper-card" no-body>
                  <b-card-header>
                    <span class="swiper-card-title"> ICEWAYS </span>
                  </b-card-header>
                  <b-card-body>
                    <p class="swiper-card-desc">
                      City life is changing. So are the habits of urban
                      citizens. 4X4 cars that were previously used only on
                      challenging lands are now preferred for urban use.
                    </p>
                    <b-row>
                      <b-col cols="6" lg="6" style="padding-right: 3px">
                        <b-button variant="outline-danger" block>
                          LEARN MORE
                        </b-button>
                      </b-col>
                      <b-col cols="6" lg="6" style="padding-left: 3px">
                        <b-button variant="danger" block>
                          FIND A DEALER
                        </b-button>
                      </b-col>
                    </b-row>
                  </b-card-body>
                </b-card>
              </swiper-slide>
              <swiper-slide>
                <b-card class="swiper-card" no-body>
                  <b-card-header>
                    <span class="swiper-card-title"> ICEWAYS </span>
                  </b-card-header>
                  <b-card-body>
                    <p class="swiper-card-desc">
                      City life is changing. So are the habits of urban
                      citizens. 4X4 cars that were previously used only on
                      challenging lands are now preferred for urban use.
                    </p>
                    <b-row>
                      <b-col cols="6" lg="6" style="padding-right: 3px">
                        <b-button variant="outline-danger" block>
                          LEARN MORE
                        </b-button>
                      </b-col>
                      <b-col cols="6" lg="6" style="padding-left: 3px">
                        <b-button variant="danger" block>
                          FIND A DEALER
                        </b-button>
                      </b-col>
                    </b-row>
                  </b-card-body>
                </b-card>
              </swiper-slide>
            </swiper>
          </b-col>
        </b-row>
        <div class="prev-button d-lg-block d-sm-none">
          <b-button variant="primary">
            <b-icon
              icon="arrow-left"
              font-scale="1.5"
              class="text-white"
              style="vertical-align: middle"
            ></b-icon>
          </b-button>
        </div>
        <div class="next-button d-lg-block d-sm-none">
          <b-button variant="primary">
            <b-icon
              icon="arrow-right"
              style="vertical-align: middle"
              font-scale="1.5"
              class="text-white"
            ></b-icon>
          </b-button>
        </div>
      </div>
      <div class="pagination-swiper text-center">
        <ul>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>
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
import { Swiper, SwiperSlide, directive } from "vue-awesome-swiper";

// import style (>= Swiper 6.x)
import "swiper/swiper-bundle.css";

// import style (<= Swiper 5.x)

export default {
  components: { Swiper, SwiperSlide },
  data() {
    return {
      swiperOption: {
        slidesPerView: 3,
        spaceBetween: 30,
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev",
        },
        pagination: {
          el: ".swiper-pagination",
        },
        breakpoints: {
          1024: {
            slidesPerView: 3,
            slidesPerGroup: 3,
            spaceBetween: 12,
          },
          768: {
            slidesPerView: 2,
            slidesPerGroup: 2,
            spaceBetween: 50,
          },
          640: {
            slidesPerView: 1,
            slidesPerGroup: 1,
            spaceBetween: 50,
          },
          480: {
            slidesPerView: 1,
            slidesPerGroup: 1,
            spaceBetween: 50,
          },
          320: {
            slidesPerView: 1,
            slidesPerGroup: 1,
            spaceBetween: 30,
          },
        },
      },
    };
  },
  layout: "Default",
};
</script>

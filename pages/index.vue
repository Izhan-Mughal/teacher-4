<template>
  <div class="jumbotron mx-lg-3 ">
    <div class="container-fluid">
      <div class="row mt-3">
        <div class="col-12 p-3 col-lg-8 col-md-8">
          <Search />
          <div class="search-main p-3 mt-4 game-slider">
            <div class="text-lg-start text-center">
              <p class="mb-0 fw-bolder mx-2 fs-5 text-green">
                Recommended Games
              </p>
            </div>
            <div class="slider-back-green mt-2 pt-2 pb-5 px-2 my-lg-3 my-2">
              <div class="text-center justify-content-center gap-2 d-flex mt-4 pt-1">
                <div class="mt-1">
                  <button class="btn-white px-3">Most Populor</button>
                </div>
                <div class="mt-1">
                  <button class="btn-white px-3">Most Recent</button>
                </div>
              </div>
              <div class="px-lg-5 justify-content-center   pb-3 px-md-3 px-sm-2 px-2  ">
                <VueSlickCarousel
                  v-bind="settings"
                  :slidesToShow="3"
                  :slidesToScroll="3"
                  :rows="2"
                  :arrows="true"
                  :dots="true"
                >
                  <div class="d-flex  mt-lg-4  justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mb-4 mt-lg-4 justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4 justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4 justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  mt-lg-4 justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  mt-lg-4 justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  <div class="d-flex mt-lg-4  mt-lg-4 justify-content-center">
                    <img
                      src="~/assets/images/Capture.png"
                      class="img-w"
                      alt=""
                    />
                  </div>
                  
                </VueSlickCarousel>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-lg-4 col-md-4 mt-3">
          <Newssec />
          <NewClass />
          <NewGame />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "MyComponent",
  components: { VueSlickCarousel },

  data() {
    return {
      settings: {
        arrows: true,
        dots: true,
        nextArrow: '<button id="Next-id">Next >',
        responsive: [
          {
            breakpoint: 1200,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
              rows: 1,
            },
          },
          {
            breakpoint: 1008,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
              rows: 1,
            },
          },
          {
            breakpoint: 800,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
              rows: 1,
              arrows: true,
            },
          },
          {
            breakpoint: 425,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
              rows: 1,
              arrows: true,
            },
          },
          {
            breakpoint: 375,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              rows: 1,
              arrows: true,
            },
          },
        ],
      },
    };
  },
};
</script>
 
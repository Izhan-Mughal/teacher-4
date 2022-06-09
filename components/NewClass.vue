<template>
  <div class="class-sec search-main p-3 mt-3">
    <div class="d-flex align-items-center mb-3 justify-content-between">
      <p class="mb-0 fw-bolder fs-5 text-blue">My Classes</p>
      <div class="text-center">
        <button class="btn-dark-blue">Veiw All</button>
        <button class="btn-blue mt-lg-0 mt-md-0 mt-2">
          <i class="fas fa-plus"></i> Create Class
        </button>
      </div>
    </div>
    <div class="mt-2 slider-back-light-blue px-2 pt-4 pb-5">
      <VueSlickCarousel
        v-bind="settings"
        :arrows="true"
        :dots="true"
        :slidesToShow="1"
        :slidesToScroll="1"
      >
        <div class="d-flex justify-content-lg-between justify-content-center ">
          <div class="search-main mx-1  p-2 d-lg-block d-none">
            <div
              class="
                slider-back-purple
                text-light
                fs-5
                p-2
                
                text-center
                fw-bolder
              "
            >
              Eleventh Grade Trignomertry
            </div>
            <div class="d-flex justify-content-evenly">
              <div class="text-center">
                <p class="fs-8 fw-bolder text-blue mb-0">24</p>
                <p class="text-blue fs-7 mb-0">Student</p>
              </div>
              <!-- <div class="text-center">
                <p class="fs-1 fw-bolder text-pink mb-0">4</p>
                <p class="text-pink fs-6 mb-0">Student</p>
              </div> -->
              <div class="text-center">
                <p class=" fw-bolder fs-8 text-green mb-0">16</p>
                <p class="text-green fs-7 mb-0">Student</p>
              </div>
            </div>
            <div class="text-center">
              <button class="btn-green mt-2">Manage Classes</button>
            </div>
          </div>
          <div class="search-main mx-1  p-2">
            <div
              class="
                slider-back-purple
                text-light
                fs-5
                p-2
                text-center
                fw-bolder
              "
            >
              Eleventh Grade Trignomertry
            </div>
            <div class="d-flex justify-content-evenly">
              <div class="text-center">
                <p class="fs-8 fw-bolder text-blue mb-0">24</p>
                <p class="text-blue fs-7 mb-0">Student</p>
              </div>
           
              <div class="text-center">
                <p class="fs-8 fw-bolder text-green mb-0">16</p>
                <p class="text-green fs-7 mb-0">Student</p>
              </div>
            </div>
            <div class="text-center">
              <button class="btn-green mt-2">Manage Classes</button>
            </div>
          </div>
        </div>
        <div class="d-flex justify-content-lg-between justify-content-center">
          <div class="search-main mx-1 p-2 d-lg-block d-none">
            <div
              class="
                slider-back-purple
                text-light
                fs-5
                p-2
                text-center
                fw-bolder
              "
            >
              Eleventh Grade Trignomertry
            </div>
            <div class="d-flex justify-content-evenly">
              <div class="text-center">
                <p class="fs-8 fw-bolder text-blue mb-0">24</p>
                <p class="text-blue fs-7 mb-0">Student</p>
              </div>
              <!-- <div class="text-center">
                <p class="fs-1 fw-bolder text-pink mb-0">4</p>
                <p class="text-pink fs-6 mb-0">Student</p>
              </div> -->
              <div class="text-center">
                <p class=" fw-bolder fs-8 text-green mb-0">16</p>
                <p class="text-green fs-7 mb-0">Student</p>
              </div>
            </div>
            <div class="text-center">
              <button class="btn-green mt-2">Manage Classes</button>
            </div>
          </div>
          <div class="search-main mx-1 p-2">
            <div
              class="
                slider-back-purple
                text-light
                fs-5
                p-2
                text-center
                fw-bolder
              "
            >
              Eleventh Grade Trignomertry
            </div>
            <div class="d-flex justify-content-evenly">
              <div class="text-center">
                <p class="fs-8 fw-bolder text-blue mb-0">24</p>
                <p class="text-blue fs-7 mb-0">Student</p>
              </div>
              <!-- <div class="text-center">
                <p class="fs-1 fw-bolder text-pink mb-0">4</p>
                <p class="text-pink fs-6 mb-0">Student</p>
              </div> -->
              <div class="text-center">
                <p class="fs-8 fw-bolder text-green mb-0">16</p>
                <p class="text-green fs-7 mb-0">Student</p>
              </div>
            </div>
            <div class="text-center">
              <button class="btn-green mt-2">Manage Classes</button>
            </div>
          </div>
       </div>
        
      </VueSlickCarousel>
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
        responsive: [
          {
            breakpoint: 1200,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              rows: 1,
            },
          },
          {
            breakpoint: 1008,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              rows: 1,
            },
          },
          {
            breakpoint: 800,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              rows: 1,
              arrows: true,
            },
          },
          {
            breakpoint: 425,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
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
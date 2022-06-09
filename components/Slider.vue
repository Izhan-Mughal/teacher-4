<template>
  <div class="hello">
    <VueSlickCarousel v-bind="settings">
      <div class="card mx-2" style="width: 18rem">
        <img class="card-img-top" src="/img/iii.webp" alt="Card image cap" />
        <div class="card-body">
          <p class="card-text text-dark"></p>
        </div>
      </div>
      
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "HelloWorld",
  components: {
    VueSlickCarousel,
  },
  data() {
    return {
      settings: {
        dots: true,
        infinite: false,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
        initialSlide: 0,
        swipe: true,
        swipeToSlide: true,
        touchMove: true,

        responsive: [
          {
            breakpoint: 1024,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              infinite: true,
              dots: false,
            },
          },
          {
            breakpoint: 600,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              initialSlide: 2,
            },
          },
          {
            breakpoint: 480,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
            },
          },
        ],
      },
    };
  },
};
</script>
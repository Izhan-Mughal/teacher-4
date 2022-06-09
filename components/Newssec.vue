<template>
  <div class="news-sec search-main p-3 pb-5">
    <div class="slider-back-blue py-4 px-5">
      <VueSlickCarousel :mode="rows" :arrows="true" :dots="true">
        <div
          class="
            my-5
            fs-5
            text-light
            d-flex
            justify-content-center
            align-items-center
          "
        >
          <p class="mb-0 fs-2 fw-bolder text-muted " >news</p>
        </div>
        <div
          class="
            my-5
            fs-5
            text-light
            d-flex
            justify-content-center
            align-items-center
          "
        >
         <p class="mb-0 fs-2 fw-bolder text-muted " >news</p>
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
};
</script>

<style scoped>
.slick-dots li button:before{
  color:blue !important; 
  font-size: 14px !important;
}
</style>
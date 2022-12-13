<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/navigation";
import "swiper/css/pagination";



// import required modules
import { Navigation, Pagination, Mousewheel, Keyboard } from "swiper";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Navigation, Pagination, Mousewheel, Keyboard],
    };
  },
};
</script>

<template>
     <section id="sliderType" class="slider__wrap">
      <div class="slider__inner">
        <div class="mainSlide__con">
           <swiper
            :cssMode="true"
            :navigation="true"
            :pagination="true"
            :mousewheel="true"
            :keyboard="true"
            :modules="modules"
            class="mySwiper"
          >
            <swiper-slide><img src="../../assets/img/main_slide_bg1.jpg"></swiper-slide>
            <swiper-slide><img src="../../assets/img/main_slide_bg2.jpg"></swiper-slide>
            <swiper-slide><img src="../../assets/img/main_slide_bg3.jpg"></swiper-slide>
          </swiper>
        </div>
      </div>
    </section>
</template>


<style>
.slider__inner {
    display: flex;
    justify-content: center;
}


.mainSlide__con {
    width: 100%;
    height: 700px;
    margin-top: 113px;
    overflow: hidden;

}


.swiper {
  width: 100%;
  height: 100%;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;

  /* Center slide text vertically */
  display: -webkit-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  -webkit-align-items: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.swiper-button-next {
  color: #fff;
}

.swiper-button-prev {
  color: #fff;
}


.swiper-pagination-bullet {
  background: #fff;
}

</style>


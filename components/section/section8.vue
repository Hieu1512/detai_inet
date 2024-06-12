<template>
  <div>
    <div class="bg-custom-color">
      <div class="w-[70%] m-auto">
        <div class="flex justify-between mt-20">
          <div class="flex">
            <p class="text-black text-4xl font-bold">Học viên nói gì</p>
            <p class="text-purple text-4xl font-bold ml-3">về chúng tôi</p>
          </div>
        </div>
      </div>
    </div>
    <div class="w-[80%] m-auto mt-5">
      <swiper
        :spaceBetween="30"
        :centeredSlides="true"
        :autoplay="{
          delay: 2500,
          disableOnInteraction: false,
        }"
        :pagination="{
          clickable: true,
        }"
        :navigation="true"
        :modules="modules"
        class="mySwiper"
      >
        <swiper-slide
          ><div>
            <div class="bg-custom-color">
              <div class="w-[87%] m-auto">
                <div class="flex mb-10">
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div></swiper-slide
        >
        <swiper-slide
          ><div>
            <div class="bg-custom-color">
              <div class="w-[87%] m-auto">
                <div class="flex mb-10">
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div></swiper-slide
        ><swiper-slide
          ><div>
            <div class="bg-custom-color">
              <div class="w-[87%] m-auto">
                <div class="flex mb-10">
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div></swiper-slide
        >
        <swiper-slide
          ><div>
            <div class="bg-custom-color">
              <div class="w-[87%] m-auto">
                <div class="flex mb-10">
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div></swiper-slide
        ><swiper-slide
          ><div>
            <div class="bg-custom-color">
              <div class="w-[87%] m-auto">
                <div class="flex mb-10">
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="w-[2%]"></div>
                  <div class="w-[35%] mt-10">
                    <div class="bg-white rounded-xl">
                      <div class="flex justify-center">
                        <p class="mt-10 mb-10 w-[85%]">
                          The web design course provided a solid foundation for me. The
                          instructors were knowledgeable and supportive, and the
                          interactive learning environment was engaging. I highly
                          recommend it!
                        </p>
                      </div>
                      <div class="custom-hr"></div>
                      <div class="w-[85%] m-auto flex">
                        <div class="flex items-center mt-5 mb-5">
                          <img class="h-12 w-12 rounded" src="/assets/anhp8/anh1.jpg" />
                          <div class="font-bold ml-3">
                            <p>Lê Minh Anh</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div></swiper-slide
        >
      </swiper>
    </div>
  </div>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";
import "swiper/css/navigation";

// import "./assets/style.css";
// import required modules
import { Autoplay, Pagination, Navigation } from "swiper/modules";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay, Pagination, Navigation],
    };
  },
};
</script>
<style>
.custom-hr {
  width: 100%; /* Chiều rộng của dòng kẻ */
  height: 1px; /* Độ dày của dòng kẻ */
  background-color: #efeffc; /* Màu sắc của dòng kẻ */
  margin: 5px 0; /* Khoảng cách trên và dưới của dòng kẻ */
  /* Các thuộc tính khác tùy ý */
}
.bg-custom-color {
  background-color: #f3f3f4;
}
</style>

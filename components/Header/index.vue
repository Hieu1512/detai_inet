<script setup></script>
<template>
  <div>
    <div class="w-[97%] m-auto py-4">
      <div class="bg-custom-color rounded px-5 py-2 text-white">
        <Nuxt-link to="/" class="flex justify-center items-center">
          Khóa học giao tiếp🌟Ưu đãi sắp kết thúc, Mua ngay
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 448 512"
            class="ml-3 w-5 h-5"
          >
            <!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.-->
            <path
              d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"
              fill="#FFFFFF"
            />
          </svg>
        </Nuxt-link>
      </div>
    </div>
    <div class="header_menu">
      <div class="mb-7 mt-3">
        <div class="flex items-center justify-center">
          <img
            class="img"
            src="https://static.ladipage.net/5b33575d031f5281797296b9/mschool-20201019033206.png"
          />
          <div class="menu flex text-sm items-center ml-10">
            <Nuxt-link to="/">Trang chủ </Nuxt-link>
            <Nuxt-link to="/page1">Tin tức </Nuxt-link>
            <Nuxt-link to="/page2">Khóa học </Nuxt-link>
            <Nuxt-link to="/">Kích hoạt khóa học </Nuxt-link>
            <Nuxt-link to="/">Liên hệ </Nuxt-link>
            <a href=""
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"
                />
              </svg>
            </a>
          </div>
          <div class="flex items-center ml-20">
            <button class="text-gray-700 font-bold py-2 px-4 rounded">Đăng nhập</button>
            <button class="ml-1 bg-custom-color text-white font-bold py-2 px-4 rounded">
              Đăng ký
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.bg-custom-color {
  background-color: #5236ff;
}

.img {
  width: 120px; /* Đặt kích thước chiều rộng tùy ý */
  height: 100%; /* Giữ tỉ lệ khung hình */
}
.header_menu {
  margin-left: 0px;
  margin-right: 0px;
}
.menu a {
  margin-left: 20px; /* Tạo khoảng cách */
}
</style>

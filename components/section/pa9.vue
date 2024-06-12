<template>
  <div>
    <div class="w-[70%] m-auto">
      <div class="flex justify-between mt-20">
        <div class="flex">
          <p class="text-black text-4xl font-bold">Đối tác</p>
          <p class="text-purple text-4xl font-bold ml-3">tiêu biểu</p>
        </div>
      </div>
      <div class="p-10">
        <div class="flex">
          <div class="w-[14.2%] m-auto">
            <div class="">
              <div class="bg-[#F3F3F4] hover:bg-[#FFFFFF] py-2 px-4">
                <img src="/assets/anhp9/anh2.png" class="w-28" />
              </div>
            </div>
          </div>
          <div class="w-[14.2%] m-auto">
            <div class="bg-[#F3F3F4] hover:bg-[#FFFFFF] py-2 px-4">
              <img src="/assets/anhp9/anh4.png" class="" />
            </div>
          </div>

          <div class="w-[14.2%] m-auto">
            <div class="bg-[#F3F3F4] hover:bg-[#FFFFFF] py-2 px-4">
              <img src="/assets/anhp9/anh5.png" class="" />
            </div>
          </div>

          <div class="w-[14.2%] m-auto">
            <div class="bg-[#F3F3F4] hover:bg-[#FFFFFF] py-2 px-4">
              <img src="/assets/anhp9/anh6.png" class="" />
            </div>
          </div>

          <div class="w-[14.2%] m-auto">
            <div class="bg-[#F3F3F4] hover:bg-[#FFFFFF] py-2 px-4">
              <img src="/assets/anhp9/anh7.png" class="" />
            </div>
          </div>

          <div class="w-[14.2%] m-auto">
            <div class="bg-[#F3F3F4] hover:bg-[#FFFFFF] py-2 px-4">
              <img src="/assets/anhp9/anh8.png" class="" />
            </div>
          </div>

          <div class="w-[14.2%] m-auto">
            <div class="bg-[#F3F3F4] hover:bg-[#FFFFFF] py-2 px-4">
              <div class="">
                <img src="/assets/anhp9/anh9.png" class="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="w-[80%] m-auto">
      <div class="flex">
        <div class="relative ml-20">
          <img src="/assets/anhp9/anh1.jpg" class="w-full rounded-md" />
          <div class="absolute top-0 left-0 right-0 bottom-0 bg-opacity-10">
            <div class="flex items-center justify-center">
              <p class="text-2xl font-bold px-4 py-2 text-[#6046FF] mt-20 mb-5">
                Nhận ưu đãi ngay
              </p>
            </div>
            <!-- <div class="flex items-center justify-center">
            <input
              type="text"
              class="border border-gray-300 rounded-md focus:outline-none focus:ring focus:border-blue-500"
            />
          </div> -->
            <div class="header__search">
              <input
                type="text"
                class="rounded header__search-input"
                placeholder="Email"
              />
            </div>
            <div class="flex justify-center py-5">
              <button class="text-white py-4 px-16 rounded bg-[#6046FF]">Gửi</button>
            </div>
          </div>
        </div>
        <div class="ml-8 mt-60">
          <button
            @click="scrollToTop"
            title="Go to top"
            class="rounded-full bottom-4 right-4 bg-[#5236ff] hover:bg-gray-600 text-white py-2 px-4"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 16 16"
              fill="currentColor"
              class="w-5 h-9"
            >
              <path
                fill-rule="evenodd"
                d="M11.78 9.78a.75.75 0 0 1-1.06 0L8 7.06 5.28 9.78a.75.75 0 0 1-1.06-1.06l3.25-3.25a.75.75 0 0 1 1.06 0l3.25 3.25a.75.75 0 0 1 0 1.06Z"
                clip-rule="evenodd"
              />
            </svg>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
const scrollToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: "smooth", // Làm cho cuộn mượt
  });
};
</script>

<style scoped>
.header__search {
  margin: 0 340px;
  height: 50px;
}

.header__search-input {
  width: 100%;
  height: 100%;
  padding: 0 16px;
}
.hover-class {
  transition: 0.3s ease;
}

.hover-class:hover {
  background-color: #ffffff;
}
input::placeholder {
  color: #5236ff; /* Thiết lập màu cho placeholder */
}
</style>

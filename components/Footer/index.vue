<script setup>
import { ref } from "vue";
let id = 0;

const createTodo = (text) => ({ id: id++, text });
const todos = ref([
  createTodo("hello@mschool.com"),
  createTodo("+0123456789"),
  createTodo("247 Cầu Giấy,Dịch Vọng,Cầu Giấy,Hà Nội"),
]);
const khampha = ref([
  createTodo("Về chúng tôi"),
  createTodo("Khóa học"),
  createTodo("Tin tức"),
  createTodo("Liên hệ"),
]);
const huongdan = ref([
  createTodo("Điều khoản dịch vụ"),
  createTodo("Chính sách đổi và hoàn tiền"),
  createTodo("Chính sách bảo mật"),
  createTodo("Chính sách thanh toán"),
]);
</script>

<template>
  <div>
    <div class="w-[70%] m-auto">
      <div class="flex items-center justify-center py-14">
        <div class="thongtin mt-10">
          <ul>
            <img
              class="img mb-10 ml-6 mt-3"
              src="https://static.ladipage.net/5b33575d031f5281797296b9/mschool-20201019033206.png"
            />
            <li v-for="todo in todos" :key="todo.id">
              <div class="mt-1"></div>
              <span v-if="todo.text === '+0123456789'" class="icon">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    fill-rule="evenodd"
                    d="M1.5 4.5a3 3 0 0 1 3-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 0 1-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 0 0 6.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 0 1 1.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 0 1-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </span>
              <span v-if="todo.text === 'hello@mschool.com'" class="icon">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    d="M1.5 8.67v8.58a3 3 0 0 0 3 3h15a3 3 0 0 0 3-3V8.67l-8.928 5.493a3 3 0 0 1-3.144 0L1.5 8.67Z"
                  />
                  <path
                    d="M22.5 6.908V6.75a3 3 0 0 0-3-3h-15a3 3 0 0 0-3 3v.158l9.714 5.978a1.5 1.5 0 0 0 1.572 0L22.5 6.908Z"
                  />
                </svg>
              </span>
              <span
                v-if="todo.text === '247 Cầu Giấy,Dịch Vọng,Cầu Giấy,Hà Nội'"
                class="icon"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  fill="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    fill-rule="evenodd"
                    d="m11.54 22.351.07.04.028.016a.76.76 0 0 0 .723 0l.028-.015.071-.041a16.975 16.975 0 0 0 1.144-.742 19.58 19.58 0 0 0 2.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 0 0-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 0 0 2.682 2.282 16.975 16.975 0 0 0 1.145.742ZM12 13.5a3 3 0 1 0 0-6 3 3 0 0 0 0 6Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </span>
              {{ todo.text }}
            </li>
          </ul>
        </div>
        <div class="daudong flex items-center mb-10">
          <ul>
            <h1 class="footer_dongdau font-bold">Khám phá</h1>
            <li v-for="todo in khampha" :key="todo.id">
              {{ todo.text }}
            </li>
          </ul>
        </div>
        <div class="daudong flex items-center mb-10">
          <ul>
            <h1 class="footer_dongdau font-bold">Hướng dẫn</h1>
            <li v-for="todo in huongdan" :key="todo.id">
              {{ todo.text }}
            </li>
          </ul>
        </div>
        <div class="daudong flex items-center mb-28">
          <ul>
            <h1 class="footer_dongdau font-bold mt-8">Theo dõi chúng tôi</h1>
            <li>
              <div class="flex mt-3">
                <div class="flex bg-[#F3F3F4] bg-opacity-90 rounded p-2">
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                  >
                    <path
                      d="M512 256C512 114.6 397.4 0 256 0S0 114.6 0 256C0 376 82.7 476.8 194.2 504.5V334.2H141.4V256h52.8V222.3c0-87.1 39.4-127.5 125-127.5c16.2 0 44.2 3.2 55.7 6.4V172c-6-.6-16.5-1-29.6-1c-42 0-58.2 15.9-58.2 57.2V256h83.6l-14.4 78.2H287V510.1C413.8 494.8 512 386.9 512 256h0z"
                    />
                  </svg>
                </div>
                <div class="flex bg-[#F3F3F4] bg-opacity-90 rounded p-2 ml-2">
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                  >
                    <path
                      d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"
                    />
                  </svg>
                </div>
                <div class="flex bg-[#F3F3F4] bg-opacity-90 rounded p-2 ml-2">
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                  >
                    <path
                      d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"
                    />
                  </svg>
                </div>
                <div class="flex bg-[#F3F3F4] bg-opacity-90 rounded p-2 ml-2">
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 496 512"
                  >
                    <path
                      d="M496 256c0 137-111 248-248 248-25.6 0-50.2-3.9-73.4-11.1 10.1-16.5 25.2-43.5 30.8-65 3-11.6 15.4-59 15.4-59 8.1 15.4 31.7 28.5 56.8 28.5 74.8 0 128.7-68.8 128.7-154.3 0-81.9-66.9-143.2-152.9-143.2-107 0-163.9 71.8-163.9 150.1 0 36.4 19.4 81.7 50.3 96.1 4.7 2.2 7.2 1.2 8.3-3.3 .8-3.4 5-20.3 6.9-28.1 .6-2.5 .3-4.7-1.7-7.1-10.1-12.5-18.3-35.3-18.3-56.6 0-54.7 41.4-107.6 112-107.6 60.9 0 103.6 41.5 103.6 100.9 0 67.1-33.9 113.6-78 113.6-24.3 0-42.6-20.1-36.7-44.8 7-29.5 20.5-61.3 20.5-82.6 0-19-10.2-34.9-31.4-34.9-24.9 0-44.9 25.7-44.9 60.2 0 22 7.4 36.8 7.4 36.8s-24.5 103.8-29 123.2c-5 21.4-3 51.6-.9 71.2C65.4 450.9 0 361.1 0 256 0 119 111 8 248 8s248 111 248 248z"
                    />
                  </svg>
                </div>
                <div class="flex bg-[#F3F3F4] bg-opacity-90 rounded p-2 ml-2">
                  <svg
                    class="h-6 w-6"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 576 512"
                  >
                    <path
                      d="M549.7 124.1c-6.3-23.7-24.8-42.3-48.3-48.6C458.8 64 288 64 288 64S117.2 64 74.6 75.5c-23.5 6.3-42 24.9-48.3 48.6-11.4 42.9-11.4 132.3-11.4 132.3s0 89.4 11.4 132.3c6.3 23.7 24.8 41.5 48.3 47.8C117.2 448 288 448 288 448s170.8 0 213.4-11.5c23.5-6.3 42-24.2 48.3-47.8 11.4-42.9 11.4-132.3 11.4-132.3s0-89.4-11.4-132.3zm-317.5 213.5V175.2l142.7 81.2-142.7 81.2z"
                    />
                  </svg>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.img {
  width: 120px;
  height: 100%;
}

.icon {
  display: inline-block;
  vertical-align: middle;
  margin-right: 5px; /* Điều chỉnh khoảng cách giữa icon và văn bản */
}
.daudong {
  margin-left: 60px;
}
</style>

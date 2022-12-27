<template>
  <section class="bg-gray-50">
    <div
      class="mx-auto max-w-screen-xl px-4 py-32 lg:flex lg:h-screen lg:items-center"
    >
      <div class="mx-auto max-w-xl text-center">
        <h1 class="text-3xl font-extrabold sm:text-5xl transition-all">
          {{ greatingText }}, я Асатулла
          <strong class="font-extrabold text-red-700 sm:block">
            Frontend разработчик
          </strong>
        </h1>

        <p class="mt-4 sm:text-xl sm:leading-relaxed">
          Я 20 летний фронтенд разработчик, который любит интересные проекты и
          сложные задачи💻
        </p>

        <div class="mt-8 flex flex-wrap justify-center gap-4">
          <a
            class="block w-full rounded bg-red-600 px-12 py-3 text-sm font-medium text-white shadow hover:bg-red-700 focus:outline-none focus:ring active:bg-red-500 sm:w-auto"
            href="#"
          >
            CV
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent, ref, onMounted } from "vue";

export default defineComponent({
  name: "HomeHeader",
  setup() {
    const greatingText = ref("Привет");
    const greatingsList = ["Привет", "Hello", "안녕하세요", "Salem"];

    onMounted(() => {
      setInterval(() => {
        greatingText.value =
          greatingsList[Math.floor(Math.random() * greatingsList.length)];
      }, 1000);
    });

    return {
      greatingText,
    };
  },
});
</script>

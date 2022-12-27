<template>
  <section class="flex flex-col justify-center items-center">
    <div class="flex flex-col justify-center items-center">
      <h2 class="text-4xl font-bold text-center text-gray-900">
        Проекты, которыми горжусь
      </h2>
    </div>

    <div class="flex space-evenly m-12">
      <article class="group mr-10">
        <img
          alt="Lava"
          src="https://i.ibb.co/m9WCQ7G/mecourse.png"
          class="h-56 w-full rounded-xl object-cover transition group-hover:grayscale-[50%]"
        />

        <div class="p-4">
          <a href="#">
            <h3 class="text-lg font-medium text-gray-900">
              Курсы по HTML, CSS и JS
            </h3>
          </a>

          <p class="mt-2 text-sm leading-relaxed text-gray-500 line-clamp-3">
            Было стяно больше 45 уроков. Далее уроки продавались онлайн академии
            программирования, где больше нескольких сотен человек проходили
            данный курс. Этот курс предназначен для начинающих, которые хотят
            изучить фундаментальные строительные блоки веб-разработки. Он
            охватывает основы HTML, CSS и JavaScript - трех основных технологий
          </p>
        </div>
      </article>
      <article class="group mr-10">
        <a href="https://ibb.co/h9nWQrM">
          <img
            src="https://i.ibb.co/DW6Ccmb/aerobee.jpg"
            alt="aerobee"
            class="h-56 w-full rounded-xl object-cover transition group-hover:grayscale-[50%]"
          />
        </a>

        <div class="p-4">
          <a href="#">
            <h3 class="text-lg font-medium text-gray-900">
              Aerobee - это приложение для автоматизации процесса de-icing'a
              самолетов
            </h3>
          </a>

          <p class="mt-2 text-sm leading-relaxed text-gray-500 line-clamp-3">
            Aerobee - это приложение для автоматизации процесса de-icing'a
            самолетов. Приложение сделано как для пилотов так и для de-icer'ов.
            Приложение позволяет пилотам узнать, какие самолеты находятся в
            очереди на де-айсинг, а также узнать, какие самолеты уже
            де-айсились. Удобный интерфейс, позволяет пилотам быстро и легко
            выбрать нужный самолет и указать участки самолета, которые нужно де-
            айсить.
          </p>
        </div>
      </article>
      <article class="group">
        <img
          alt="SDF 2022 награда"
          src="https://i.ibb.co/YZWzb2t/me.jpg"
          class="h-56 w-full rounded-xl object-cover shadow-xl transition group-hover:grayscale-[50%]"
        />

        <div class="p-4">
          <a href="#">
            <h3 class="text-lg font-medium text-gray-900">
              KazEnergy - автоматизация процесса выброса отходов
            </h3>
          </a>

          <p class="mt-2 text-sm leading-relaxed text-gray-500 line-clamp-3">
            KazEnergy - автоматизация процесса выброса отходов. Сделано в рамках
            конкурсах Student Digital Fest 2022. Приложение разделено на разные
            роли. Для администратора, который может добавлять новых
            пользователей, удалять их, а также просматривать статистику. Для
            пользователя, который может добавлять новые отходы, просматривать
            статистику, а также просматривать свои отходы.
          </p>
        </div>
      </article>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>


<template>
  <BaseApp1Right>
    <template v-slot:header>
      Программирование
    </template>
    <template v-slot:main>
      <h1>Что такое программирование?</h1>
      <p>
        Программирование — это процесс создания компьютерных программ или программного обеспечения, а также дисциплина,
        изучающая методы и приёмы создания и развития компьютерных программ.
      </p>
      <img
          src="https://fikiwiki.com/uploads/posts/2022-02/1644890738_15-fikiwiki-com-p-kartinki-yazikov-programmirovaniya-18.jpg"
          width="50%"
          alt="code"/>
      <p>
        Программирование включает следующие этапы:
      </p>
      <ul>
        <li>Анализ предметной области</li>
        <li>Проектирование программы</li>
        <li>Кодирование</li>
        <li>Выявление дефектов и ошибок при помощи тестирования и других методов верификации</li>
        <li>Развёртывание</li>
        <li>Сопровождение</li>
      </ul>
      <p>
        Как дисциплина программирование изучает принципы построения и функционирования программ, используя методы и
        технические приёмы, а также способы организации как крупных программных систем, так и небольших элементов
        программ.
      </p>
      <p>
        В зависимости от поставленных целей, размерности задачи, методов решения различают параллельное
        программирование, распределённое программирование и др. Языки программирования поддерживают различные стили
        программирования (парадигмы программирования). В искусство программирования входит выбор языка программирования,
        наиболее полно подходящего для решения поставленной задачи.
      </p>
      <br/>
      <br/>
      <img
          src="https://flomaster.top/uploads/posts/2023-01/1673554913_flomaster-club-p-utochka-dlya-vanni-risunok-vkontakte-57.jpg"
          width="50%" alt="utochka"/>
    </template>
    <template v-slot:aside>
      <h2>Статьи</h2>
      <ul>
        <li>
          <NuxtLink to="/web/prog/lang">Языки программирования</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/web/prog/back-front">Frontend и Backend</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/web/prog/linux">Что такое Linux?</NuxtLink>
        </li>
      </ul>
      <h2>Анкета</h2>
      <p>
        <NuxtLink to="/web/prog/what-lang">Какие ЯП Вы знаете?</NuxtLink>
      </p>
      <img
          src="https://zifra42.ru/wp-content/uploads/2023/02/%D0%92%D1%81%D1%82%D1%80%D0%B5%D1%87%D0%B0-%D1%81-%D0%B4%D0%B5%D0%B2%D1%8F%D1%82%D0%B8%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%BD%D0%B8%D0%BA%D0%B0%D0%BC%D0%B8-%D0%A1%D0%9E%D0%A8-%E2%84%9616-%D0%B3.-%D0%9A%D0%B5%D0%BC%D0%B5%D1%80%D0%BE%D0%B2%D0%BE_1-1300x731.jpg"
          width="95%" alt="laptop and programming"/>
    </template>
  </BaseApp1Right>
</template>


<style scoped lang="scss">
@import "/styles/base";
</style>

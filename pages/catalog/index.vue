<script setup lang="ts">
</script>


<template>
  <BaseApp1Right>
    <template v-slot:header>Каталог</template>
    <template v-slot:main>
      <h1>Каталог</h1>
      <h2>Все сервисы</h2>
      <ul>
        <li>
          <NuxtLink to="/services/music">Музыка</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/services/video">Видео</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/services/photo">Фото</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/help">Помощь</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/tech-support">Техподдержка</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/feedback">Написать отзыв</NuxtLink>
        </li>
      </ul>
      <h2>Темы</h2>
      <p>Темы - это объединение нескольких записей в одну группу по схожей тематике.</p>
      <ul>
        <li>
          <NuxtLink to="/web/vsoh">ВСОШ</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/web/cats">Котики</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/web/prog">Программирование</NuxtLink>
        </li>
      </ul>

    </template>
    <template v-slot:aside>
      <h4>Последние записи</h4>
      <ul>
        <li>Пусто</li>
      </ul>
      <p>Точно не реклама</p>
      <img src="/images/tech-support.webp" width="90%" alt="tech-support"/>
    </template>
  </BaseApp1Right>
</template>


<style scoped lang="scss">
@import "/styles/base";
</style>

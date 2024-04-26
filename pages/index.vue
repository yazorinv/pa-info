<script setup lang="ts">
useSeoMeta({
      title: "Главная страница"
    }
)
</script>


<template>
  <BaseApp1Right>
    <template v-slot:header>Главная страница</template>
    <template v-slot:main>
      <h1>Добро пожаловать</h1>
      <code>Hello, World!</code>
      <p>На этом сайте Вы можете найти множество различной информации и сервисов. Все разделы можно увидеть во вкладке
        <NuxtLink to="/catalog">Каталог.</NuxtLink>
      </p>
      <p>Приятного пользования!</p>
    </template>
    <template v-slot:aside>
      <p>Точно не реклама</p>
      <img src="/images/tech-support.webp" width="90%" alt="tech-support"/>
    </template>
  </BaseApp1Right>
</template>


<style scoped lang="scss">
@import "styles/base.scss";
</style>

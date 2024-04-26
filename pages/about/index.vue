<script setup lang="ts">
</script>


<template>
  <BaseApp1Right>
    <template v-slot:header>О нас</template>
    <template v-slot:main>
      <img src="/images/shaman.webp" class="shaman" alt="shaman"/>
      <h1>О нас</h1>
      <p>Это мой небольшой сайт, на котором Вы можете найти множество различной информации и сервисов.</p>
      <p>Всё разделы можно увидеть во вкладке
        <NuxtLink to="/catalog">Каталог.</NuxtLink>
      </p>
      <h4>При создании использовалось следующее:</h4>
      <ul>
        <li><a href="https://nuxt.com"><code>Nuxt 3</code></a></li>
        <li><a href="https://vuejs.com"><code>Vue JS 3</code></a></li>
        <li><a href="https://sass-lang.com"><code>Sass (Scss)</code></a></li>
        <li><a href="https://github.com/catppuccin/catppuccin">Catppuccin Theme</a></li>
      </ul>
      <p>Сайт уже лежит на <a href="https://github.com/yazorinv/pa-info"><code>GitHub</code></a> и <a
          href="https://yandex.cloud">Yandex Cloud</a>.</p>
    </template>
    <template v-slot:aside>
      <img src="/images/flatppuccin_green.webp" width="100%" alt="flatppuccin_green"/>
      <img src="/images/dark-cat.webp" width="100%" alt="dark-cat"/>
    </template>
  </BaseApp1Right>
</template>


<style scoped lang="scss">
@import "/styles/base";


.shaman {
  width: 40%;
  float: right;
}
</style>

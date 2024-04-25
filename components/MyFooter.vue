<script setup lang="ts">
</script>


<template>
  <footer>
    <address>
      <h1>Контакты</h1>
      <h2>Телефон</h2>
      <a href="tel:+7 999 999 99 99">+7 999 999 99 99</a>
      <h2>Email</h2>
      <a href="mailto:example@example.com">example@example.com</a>
      <h2>Адрес</h2>
      <p>г. Москва, ул. Ленина, д. 1</p>
      <h2>Социальные сети</h2>
      <ul>
        <li><a href="https://vk.com">VK</a></li>
        <li><a href="https://t.me">Telegram</a></li>
        <li><a href="https://discord.com">Discord</a></li>
      </ul>
    </address>
    <address>
      <h1>Полезные ссылки</h1>
      <ul>
        <li><a href="https://nuxt.com">Nuxt</a></li>
        <li><a href="https://github.com">GitHub</a></li>
        <li><a href="https://vuejs.org">Vue JS</a></li>
      </ul>
      <h2>Мой GitHub</h2>
      <a href="https://github.com/yazorinv">GitHub</a>
    </address>
    <address>
      <h1>Навигация</h1>
      <ul>
        <li>
          <NuxtLink to="/">Главная</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/catalog">Каталог</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">О проекте</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/contacts">Контакты</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/feedback">Написать отзыв</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/help">Помощь</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/tech-support">Техподдержка</NuxtLink>
        </li>
      </ul>
    </address>
    <div class="wrap">
      <div>
        <p><a href="https://github.com/yazorinv/pa-info">GitHub этого проекта</a></p>
        <p><a href="https://github.com/yazorinv/pa-info/blob/master/LICENSE">Лицензия</a></p>
        <p><a href="https://github.com/yazorinv/pa-info/blob/master/README.md">Описание</a></p>
        <MyButtonTheme class="sm"/>
      </div>
      <div>
        <MyLogo class="sm"/>
      </div>
    </div>
  </footer>
</template>


<style scoped lang="scss">
@import "/styles/boxing";
@import "/styles/colors";
@import "/styles/fonts";


footer {
  @extend %boxing;

  background-color: $base;
  font-family: "Roboto", sans-serif;
  font-size: $size-2;
  color: $text;

  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: stretch;
  align-content: flex-start;


  h1, h2, a, p, code {
    margin: 10px;
  }

  h1 {
    font-family: "Roboto", sans-serif;
    font-size: $size-6;
    color: $text;
  }

  h2 {
    font-family: "Roboto", sans-serif;
    font-size: $size-5;
    color: $text;
  }

  a, p, li {
    font-family: "Roboto", sans-serif;
    font-size: $size-3;
    color: $teal;

    text-decoration: none;
  }


  .wrap {
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: space-between;
    align-items: stretch;
    align-content: stretch;

    a, p {
      font-family: "JetBrains Mono", monospace;
    }

    .sm {
      margin: 10px;
      float: right;
    }
  }
}
</style>

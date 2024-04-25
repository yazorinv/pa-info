<script setup>
const props = defineProps({
  lst: {
    type: Array,
    default: () => [["Главная", "/"], ["Каталог", "/catalog"], ["Контакты", "/contacts"], ["О нас", "/about"]]
  }
})
</script>


<template>
  <nav>
    <NuxtLink v-for="item in props.lst" :to="item[1]">{{ item[0] }}</NuxtLink>
  </nav>
</template>


<style scoped lang="scss">
@import "/styles/boxing";
@import "/styles/colors";
@import "/styles/fonts";


nav {
  @extend %boxing;

  background-color: $surface0;
  font-family: "Roboto", sans-serif;
  font-size: $size-2;
  color: $text;

  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
  align-content: flex-start;

  a {
    font-family: "Lobster", sans-serif;
    font-size: $size-5;
    color: $text;

    text-decoration: none;
  }
}
</style>

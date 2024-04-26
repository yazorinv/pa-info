<script setup lang="ts">
</script>


<template>
  <MyHeader>Error 404</MyHeader>
  <main>
    <h2>Это не та страница, которую вы ищете</h2>
    <h5>
      <a href="/">Вернуться на главную</a>
    </h5>
    <img src="/images/not-droid.webp" alt="not-droid"/>
  </main>
</template>


<style scoped lang="scss">
@import "/styles/base";

main {
  text-align: center;

  h2 {
    color: $red;
  }

  img {
    width: 60%;
  }
}
</style>

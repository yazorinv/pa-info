<script setup lang="ts">
</script>


<template>
  <BaseApp1Right>
    <template v-slot:header>Помощь</template>
    <template v-slot:main>
      <img src="/images/cats/17.webp" alt="cat-help"/>
      <h1>Помощь</h1>
      <p>Ничем помочь не можем, у нас лапки</p>
    </template>
    <template v-slot:aside>
      <p>Возможно вам нужна
        <NuxtLink to="/tech-support">техподдержка</NuxtLink>
      </p>
      <p>...</p>
    </template>
  </BaseApp1Right>
</template>


<style scoped lang="scss">
@import "/styles/base";

img {
  float: right;
  width: 50%;
}
</style>

<script setup lang="ts">
</script>


<template>
  <BaseApp1Right>
    <template v-slot:header>Техподдержка</template>
    <template v-slot:main>
      <img src="/images/tech-support.webp" alt="tech-support"/>
      <h1>Техподдержка</h1>
      <code>Перезагрузите компьютер!</code>
    </template>
    <template v-slot:aside>
      <p>Возможно вам нужна
        <NuxtLink to="/help">помощь</NuxtLink>
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

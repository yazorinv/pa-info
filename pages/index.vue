<script setup lang="ts">
import BaseApp0 from "~/layouts/BaseApp0.vue";
</script>


<template>
  <BaseApp0>
    <template v-slot:header>Hello</template>
    <template v-slot:main>
      <h1>Всем привет</h1>
    </template>
  </BaseApp0>
</template>


<style scoped lang="scss">
@import "styles/base";
</style>

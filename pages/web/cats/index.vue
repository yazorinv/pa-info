<script setup lang="ts">
</script>


<template>
  <BaseApp0>
    <template v-slot:header>
      Котики
    </template>
    <template v-slot:main>
      <h1>Мой кот. Фото</h1>
      <p>Его кстати зовут Геракл</p>
      <div class="wrap">
        <img v-for="i in Array.from(Array(34).keys())" :src="`/images/cats/${i.toString()}.webp`" width="30%"
             alt="cat"/>
      </div>
    </template>
  </BaseApp0>
</template>


<style scoped lang="scss">
@import "/styles/base";

img {
  margin: 1rem;
}

.wrap {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  align-content: flex-start;
}

</style>

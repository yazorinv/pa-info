<script setup lang="ts">
useSeoMeta({
      title: "Котики"
    }
)
</script>


<template>
  <BaseApp0>
    <template v-slot:header>
      Котики
    </template>
    <template v-slot:main>
      <h1>Котики Вероники. Фото</h1>
      <div class="wrap">
        <img v-for="i in Array.from(Array(10).keys())" :src="`/images/new_cats/${i.toString()}.jpg`" width="30%"
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

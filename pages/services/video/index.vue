<script setup lang="ts">
</script>


<template>
  <BaseApp0>
    <template v-slot:header>Видео</template>
    <template v-slot:main>
      <h2>Просто посмотрите парочку видео</h2>
      <figure>
        <h5>Море</h5>
        <video width="640" height="360" src="/video/video-sea.mp4" controls/>
      </figure>
      <figure>
        <h5>Кот</h5>
        <video width="640" height="360" src="/video/cat.mp4" controls/>
      </figure>
    </template>
  </BaseApp0>
</template>


<style scoped lang="scss">
@import "/styles/base";


.shaman {
  width: 40%;
  float: right;
}
</style>

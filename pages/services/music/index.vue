<script setup lang="ts">
useSeoMeta({
      title: "Музыка"
    }
)
</script>


<template>
  <BaseApp0>
    <template v-slot:header>Музыка</template>
    <template v-slot:main>
      <img src="/images/shaman.webp" class="shaman" alt="shaman"/>
      <h1>Музыка</h1>
      <h2>Просто послушайте музыку и отдохните</h2>
      <figure>
        <h5> Лунная соната</h5>
        <audio src="/music/lunnaya-sonata.mp3" controls/>
      </figure>
      <figure>
        <h5>Шаман "Я русский"</h5>
        <audio src="/music/shaman-ya-russkiy.mp3" controls/>
      </figure>
      <figure>
        <h5> Filatov & Karas, GAYAZOV$ BROTHER$ "Пошла жара"</h5>
        <audio src="/music/filatov-poshla-zhara.mp3" controls/>
      </figure>
      <figure>
        <h5> GAYAZOV$ BROTHER$ "Малиновая лада"</h5>
        <audio src="/music/gayazov-malinovaia-lada.mp3" controls/>
      </figure>
      <figure>
        <h5> Король и Шут "Лесник"</h5>
        <audio src="/music/kish-lesnik.mp3" controls/>
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

<script setup lang="ts">
const props = defineProps({
  logo_light: {
    type: String,
    default: '/images/logo-light.webp'
  },
  logo_dark: {
    type: String,
    default: '/images/logo-dark.webp'
  },
  height: {
    type: String,
    default: '128px'
  }
})

const colorMode = useColorMode()
</script>


<template>
  <NuxtLink to="/">
    <img :src="colorMode.value === 'light' ? logo_light : logo_dark" :height="height" alt="logo"/>
  </NuxtLink>
</template>


<style scoped lang="scss">
@import "styles/colors";
@import "styles/fonts";


a, img {
  font-family: "Roboto", sans-serif;
  font-size: $size-2;
  color: $red;

  text-decoration: none;
}
</style>

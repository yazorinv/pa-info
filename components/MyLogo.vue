<script setup lang="ts">
const props = defineProps({
  logo_light: {
    type: String,
    default: '/logo-light.png'
  },
  logo_dark: {
    type: String,
    default: '/logo-dark.png'
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
    <img v-if="colorMode.value === 'dark'" :src="logo_dark" :height="height" alt="logo"/>
    <img v-else :src="logo_light" :height="height" alt="logo"/>
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

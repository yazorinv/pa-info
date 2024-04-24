<script setup lang="ts">
</script>


<template>
  <header>
    <MyLogo/>
    <h1>
      <slot>Hello</slot>
    </h1>
    <MyButtonTheme/>
  </header>
</template>


<style scoped lang="scss">
@import "/styles/boxing";
@import "/styles/colors";
@import "/styles/fonts";


header {
  @extend %boxing;

  background-color: $base;
  font-family: "Roboto", sans-serif;
  font-size: $size-2;
  color: $text;

  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  align-content: flex-start;

  h1 {
    font-family: "Lobster", sans-serif;
    font-size: $size-10;
    color: $text;

    text-align: center;
    flex-grow: 10;
  }
}
</style>

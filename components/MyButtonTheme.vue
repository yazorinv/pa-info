<script setup lang="ts">
const colorMode = useColorMode()


function toggleColorMode() {
  colorMode.preference = colorMode.value === 'light' ? 'dark' : 'light'
}
</script>


<template>
  <button @click="toggleColorMode">
    <div class="in-button"></div>
  </button>
</template>


<style scoped lang="scss">
@use "sass:math";

$light: #e6e9ef;
$dark: #181825;
$my-size: 40px;


button {
  width: $my-size + 10px;
  height: $my-size + 10px;
  border-radius: 10px;
  border: none;

  padding: 5px;
  margin: 5px;

  cursor: pointer;
}

.light-mode button {
  background-color: $dark;
}

.dark-mode button {
  background-color: $light;
}


.in-button {
  width: $my-size;
  height: $my-size;
  border-radius: math.div($my-size, 2);
  transition: 0.3s;
}

.light-mode .in-button {
  top: math.div($my-size, 2);
  left: math.div($my-size, 2);
  box-shadow: inset math.div($my-size, 4) math.div(-$my-size, 8) 0 0 $light;
  background-color: $dark;
}

.dark-mode .in-button {
  background-color: $dark;
}


</style>

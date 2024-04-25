<script setup lang="ts">
</script>


<template>
  <div>
    <MyHeader class="mx">
      <slot name="header"/>
    </MyHeader>
    <MyMenu class="mx"/>
    <main class="mx">
      <slot name="main"/>
    </main>
    <MyFooter class="mx"/>
  </div>
</template>


<style scoped lang="scss">
@import "/styles/base";

.mx {
  width: 100%;
}
</style>

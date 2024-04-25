<script setup lang="ts">
</script>


<template>
  <div>
    <MyHeader>
      <slot name="header"/>
    </MyHeader>
    <MyMenu/>
    <main>
      <slot name="main"/>
    </main>
    <MyFooter/>
  </div>
</template>


<style scoped lang="scss">
@import "/styles/base";
</style>

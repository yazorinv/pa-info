<script setup lang="ts">
</script>


<template>
  <div class="wrap">
    <MyHeader class="mx">
      <slot name="header"/>
    </MyHeader>
    <MyMenu class="mx"/>
    <aside>
      <slot name="aside"/>
    </aside>
    <main>
      <slot name="main"/>
    </main>
    <MyFooter class="mx"/>
  </div>
</template>


<style scoped lang="scss">
@import "/styles/base";

.wrap {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: stretch;
  align-content: flex-start;

  .mx {
    width: 100%;
  }
}
</style>

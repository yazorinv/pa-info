<script setup lang="ts">
</script>


<template>
  <div>
    <MyHeader>
      <slot name="header"/>
    </MyHeader>
    <MyMenu/>
    <div class="wrap">
      <aside>
        <slot name="aside1"/>
      </aside>
      <main>
        <slot name="main"/>
      </main>
      <aside>
        <slot name="aside2"/>
      </aside>
    </div>
    <MyFooter/>
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
}

@media all and (min-width: 800px) {
  .wrap {
    flex-wrap: nowrap;
  }
}
</style>

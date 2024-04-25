<script setup lang="ts">
</script>


<template>
  <div>
    <MyHeader>
      <slot name="header"/>
    </MyHeader>
    <MyMenu/>
    <div class="wrap">
      <main>
        <slot name="main"/>
      </main>
      <aside>
        <slot name="aside"/>
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

@media all and (min-width: 600px) {
  .wrap {
    flex-wrap: nowrap;
  }
}
</style>

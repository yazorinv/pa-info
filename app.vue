<template>
  <NuxtPage/>
</template>

<style lang="scss">
@import "/styles/base-colors.scss";
@import "/styles/colors.scss";


body {
  background-color: $crust;
  padding-left: 10%;
  padding-right: 10%;
}

.dark-mode body {
  background: $crust url("/background-dark.png") no-repeat;
}


.page-enter-active,
.page-leave-active {
  transition: all 0.5s;
}

.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
</style>
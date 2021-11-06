<template>
  <div class="default-layout">
    <TheNavBar />
    <slot />
  </div>
</template>

<style lang="scss" scoped>
.default-layout {
  width: 90vw;
  max-width: 600px;
  margin: auto;
}
</style>

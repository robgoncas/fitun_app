<template>
  <div id="app">
    <div class="layout">
      <router-view />
    </div>
  </div>
</template>

<style lang="postcss">
.layout {
  @apply absolute inset-0;
}
</style>

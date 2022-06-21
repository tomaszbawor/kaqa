<script lang="ts" setup></script>

<template>
  <div class="wrapper">
    <div class="side"><TheSidebar /></div>
    <div class="content">
      <slot />
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
}

.side {
  max-width: 400px;
}

.content {
  padding: 10px;
}
</style>

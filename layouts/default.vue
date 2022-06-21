<script lang="ts" setup>
import TheSidebar1 from "~~/components/TheSidebar.vue";
</script>

<template>
  <div class="content">
    <TheSidebar />
    <slot />
  </div>
</template>

<style scoped>
.content {
  background-color: red;
}
</style>

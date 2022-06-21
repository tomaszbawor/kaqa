<script lang="ts" setup></script>

<template>
  <div :class="$style.wrapper">
    <div :class="$style.logo">LOGO</div>
    <ul>
      <li><NuxtLink href="/">Main</NuxtLink></li>
      <li><NuxtLink href="/about">About</NuxtLink></li>
    </ul>
  </div>
</template>

<style module>
.wrapper {
  display: flex;
  width: 100%;
  display: flex;
  flex-direction: column;
  border: 1px solid red;
  padding: 5px;
}

.logo {
  padding: 10px;
}
</style>

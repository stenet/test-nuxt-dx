<script lang="ts" setup>
</script>

<template>
  <div class="h-screen flex flex-col gap-4 m-4">
    <TheNav />
    <TheContent class="grow">
      <slot></slot>
    </TheContent>
  </div>
</template>

<style lang="less">
</style>
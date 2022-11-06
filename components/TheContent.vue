<script lang="ts" setup>
import DxScrollView from "devextreme-vue/scroll-view";
</script>

<template>
  <div class="h-full relative">
    <div class="absolute inset-0">
      <!-- tried to wrap inside ClientOnly => ends in error -->
      <DxScrollView
        height="100%">
        <slot></slot>
      </DxScrollView>
    </div>
  </div>
</template>

<style lang="less">
</style>